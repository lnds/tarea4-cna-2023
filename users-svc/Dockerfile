# syntax=docker/dockerfile:1

FROM node:18-alpine

WORKDIR /usr/app

COPY package.json .

RUN npm install --quiet

COPY ./ ./

RUN npm run build

FROM nginx:stable-alpine AS build-release-stage

WORKDIR /

COPY --from=build-stage /usr/app/dist /usr/share/nginx/html
