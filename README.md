# Lab W2D3 — Containerise v1 Serving Service

## Overview

Containerised the `/v1` serving service using Docker. The application is packaged as a lightweight CPU-based image, while the Hugging Face model weights remain outside the image in a persistent Docker volume.

## Docker Image

```text
almohamadiii/aidc-serving:cpu-v1
