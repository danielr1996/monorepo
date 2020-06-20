# monorepo

I'm collecting ideas for a monorepo tool that I'm missing from other tools like lerna and I will code someday (aka never)

* No replacement for npm/yarn, use with whatever tool you like
* Generic command to execute in every package or just some packages, e.g.
  * monorepo run npm install typescript
  * monorepo run --packages a b npm install typescript
