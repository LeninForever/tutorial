# Clickhouse

## 1. Развёртывание в контейнере Docker

Создание общей сети, в которой будут находиться контейнеры

`docker network create tutorial`

Создание volume для контейнера Clickhouse

`docker volume create clickhouse-volume`

Далее

`docker compose up -d`

## 2.