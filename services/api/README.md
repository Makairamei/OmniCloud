# OmniCloud API

Backend Node.js untuk proxy metadata, upload stream, WebSocket progress, dan sinkronisasi delta.

## Environment
- `GOOGLE_CLIENT_ID`
- `GOOGLE_CLIENT_SECRET`
- `GOOGLE_REDIRECT_URI`
- `ONEDRIVE_CLIENT_ID`
- `ONEDRIVE_CLIENT_SECRET`
- `ONEDRIVE_TENANT_ID`
- `ONEDRIVE_REDIRECT_URI`

## Endpoint utama
- `GET /api/health`
- `GET /api/accounts`
- `GET /api/files?path=/`
- `POST /api/uploads/initiate`
- `POST /api/uploads/:uploadId/stream`
- `GET /api/files/:id/download`
- `WS /ws/uploads?uploadId=...`
