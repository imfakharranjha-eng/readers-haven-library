# Readers Haven Library

A static library website built with HTML5 and CSS3, bundled using Parcel and containerized with Docker.

## Technologies
- HTML5
- CSS3
- Node.js 22
- Parcel
- Docker
- Nginx 1.27 Alpine

## Website Pages
- Home
- Collections
- Membership
- Services
- Contact

## Run Locally

Install dependencies:

```bash
npm ci
```

Build the website:

```bash
npm run build
```

## Build Docker Image

```bash
docker build -t readers-haven-library:v1 .
```

## Run Docker Container

```bash
docker run -d -p 8080:80 --name readers-haven-container readers-haven-library:v1
```

Open http://localhost:8080 in your browser.

## Docker Hub

Image: `bossmarky/readers-haven-library:v1`

Pull command:

```bash
docker pull bossmarky/readers-haven-library:v1
```
