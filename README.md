# UniSocial

This is a [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`.

## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with just the scaffolding we set up for you, and add additional things later when they become necessary.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

## How do I run this?

We use pnpm instead of yarn or npm. 99% of npm commands transate to the same in pnpm, why pnpm? [here](https://pnpm.io/)

## How do I deploy this?

Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.

## Commit & Push

We set up rules that run before every commit or push - achieved by using 2 tools:

1. [husky](https://typicode.github.io/husky)
2. [commitlint](https://commitlint.js.org/#/reference-rules)

- All commit messages should follow the guidline referenced above
- Pre-Commit - Will run lint on codebase to catch errors & ensure code style.
- Pre-Push - Will run a build to make sure production does not break. (we will be in production soon enough)
