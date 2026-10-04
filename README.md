# EKL Search System — Server Ready

## What it does
- Chrome/mobile friendly EKL search
- REST API: `/api/ekls` and `/api/ekl/:ekl`
- Demo data imported from `M&S.xlsx`
- Easy to deploy to Render, Railway, VPS or an internal server

## Run on a computer/server
1. Install Node.js 18+
2. Open this folder in terminal
3. Run `npm install`
4. Run `npm start`
5. Open `http://localhost:3000` in Chrome

## Production next step
Replace the JSON data layer with PostgreSQL/MySQL and add login/roles. Then the same frontend can search live production data by EKL.
