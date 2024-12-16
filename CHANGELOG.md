# 1.0.0
- The initial rewrite to Astro. Includes:
    - Fully static
    - Easier to build
    - Feels/is faster to use
    - Fixes some bugs
    - Among tons of other stuff

# 1.0.1
- Fixes the games and apps page looking weird

# 1.0.2
- Fixes Dockerfile issues

# 1.0.3
- Turns off Rammerhead by default for now
- Docker env fixes again
- SEO

# 1.0.4
- Bumps RH
- Fixes issues with bare-server-node

# 1.1.0
- Switches to Deno (mostly)
- General bug fixes
- Removes Rammerhead as an option and replaces it with Scramjet (coming soon)
- Removes bare server and adds libcurl as an option
- Adds a different Deno native server (Hono) - Command: `deno task start:standalone`
- Removes Masqr
- No more SSR, it's purely statically generated
- CI fixes and other general improvements
- Configuration is done via TOML over a bunch of environment vars
- Removes Biome in place of Deno's native formatter
- A better roadmap of what should be done in the future.