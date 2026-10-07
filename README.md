# Firestore CRUD API

An Express API demonstrating create, read, update, and delete operations with Firebase Admin.

## What is included

- Routes: `POST /create`, `GET /read/all`, `GET /read/:id`, `POST /update`, `DELETE /delete/:id`.

## Getting started

Configure a separate Firebase development project and private credentials in place of the checked-in `key.json`. Run `npm install`, then `npm start`. Use the port printed by `server.js` and inspect its expected request fields.

## Repository guide

- `README.md`
- `package-lock.json`
- `package.json`
- `server.js`

## Limitations and reproducibility

Rotate the committed service-account credentials before reuse. Tracked dependencies should be replaced with a clean local installation. The test command is a placeholder; this is an instructional API, not a hardened public service.
