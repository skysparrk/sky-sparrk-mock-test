# Sky Sparrk Integrated V2

Real SQLite database + integrated student/admin website.

Includes:
- Student registration/login
- Timed mock tests
- Server-side scoring
- Persistent attempts
- Admin dashboard
- Create and publish tests
- Add questions
- Admin statistics

Run:
1. npm install
2. Set JWT_SECRET to a strong random value
3. npm start
4. Open http://localhost:3000

For production: use HTTPS, secure admin provisioning, backups, rate limiting and preferably PostgreSQL at scale.
