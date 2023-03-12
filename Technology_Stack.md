| Category | Platters | Recordz
|----------|----------|--------
| Framework | Ruby On Rails | SvelteKit
| Language | Ruby | TypeScript
| REPL | rails c / pry | ?
| JS Library | jQuery | -
| CSS Frameworkd | Bootstrap | Pico or Tailwind + daisyUI or Skeleton
| Storage | Postgres | CockroachDB / Planetscale
| Text Search | Postgres '@@' | CockroachDB trigram index (v22.2) with % operator? (1)
| Jobs Processor | Sidekiq | ?
| ORM | ActiveRecord | Prisma (no polymorphic association), Drizzle ORM (3), Kysely
| Page Cache | cache_store + Redis | ? upstash (2)
| Deployment | Digital Ocean Droplet | Vercel
| Image Processing | CarrierWave (local & API) | (local & API)?
| Image Hosting | Rackspace Cloud Files | Cloudflare R3
| Image Resizing | ImageMagick | ?
| Icon Library | Font Awesome | unplugin-icons
| Authentication | Clearance | Lucia?
| Captcha | invisible_captcha | Cloudflare Turnstile?
| Profanity filter | obscenity | ?
| Email | Mailgun | ?
| Performance Monitoring | Skylight | Vercel?
| Log tracking | Rollbar | Axiom?
| Testing framework | Rspec (Model, Request & E2E) | Vitest (Unit, Component & E2E)?
| End to end testing | Selenium + Headless Chrome | Cypress or Playwright

- (1) See: [Trigram Indexes](https://www.cockroachlabs.com/docs/stable/trigram-indexes.html) and [Use cases for trigram indexes](https://www.cockroachlabs.com/blog/use-cases-trigram-indexes)
- (2) See: [Speed up SvelteKit Pages With a Redis Cache](https://www.captaincodeman.com/speed-up-sveltekit-pages-with-a-redis-cache)
- (3) See: [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)

- Checkout Prisma studio: npx prisma studio
