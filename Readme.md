# Reason of this repo

This repo is created to show best providers of different services.

## Free Database Cloud Providers
- PostgreSQL:
    - [NEON](https://neon.tech/)
        - **ENV**: DATABASE_URL=
    - [Supabase](https://supabase.com/) (Firebase alternative)
        - **ENV**: DATABASE_URL=
- MongoDB:
    - [MongoDB](https://cloud.mongodb.com/)
        - **ENV**: DATABASE_URL=
- MySQL:
    - [Clever Cloud](https://console.clever-cloud.com/)
        - **ENV**: DATABASE_URL=
- Cloudflare D1:
    - [Cloudflare D1](https://developers.cloudflare.com/d1/platform/pricing/)
        - **ENV**: DATABASE_URL=

## Paid Database Cloud Providers


## Database ORM
- [Prisma](https://www.prisma.io/nextjs): PostgreSQL, MySQL/MariaDB, SQLite, MongoDB, SQL Server, CockroachDB
    - **ENV**: DATABASE_URL= (from Cloud Provider)

## Auth Solution
- [NextAuth](https://next-auth.js.org/)
    - **ENV**: NEXTAUTH_SECRET= with random string
- Auth0:
- Kinde:

## Auth API
- [Google OAuth Client](https://console.cloud.google.com/apis/credentials/oauthclient)
    - **ENV**:
        - GOOGLE_CLIENT_ID=
        - GOOGLE_CLIENT_SECRET=
    - **Configuration**:
        - (new project, web application)
        - Javascript origin: <http://localhost:3000> (for local development)
        - Redirect URI: 
            - <http://localhost:3000/api/auth/callback/google>
            - <https://YOUR_DOMAIN/api/auth/callback/google>
- 