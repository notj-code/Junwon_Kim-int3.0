10:00:01 PM: Netlify Build                                                 
10:00:01 PM: ────────────────────────────────────────────────────────────────
10:00:01 PM: ​
10:00:01 PM: ❯ Version
10:00:01 PM:   @netlify/build 35.1.2
10:00:01 PM: ​
10:00:01 PM: ❯ Flags
10:00:01 PM:   accountId: 6597baa848019a980272ce02
10:00:01 PM:   baseRelDir: true
10:00:01 PM:   buildId: 68ac5e3ce394270008083165
10:00:01 PM:   deployId: 68ac5e3ce394270008083167
10:00:01 PM: ​
10:00:01 PM: ❯ Current directory
10:00:01 PM:   /opt/build/repo
10:00:01 PM: ​
10:00:01 PM: ❯ Config file
10:00:01 PM:   No config file was defined: using default values.
10:00:01 PM: ​
10:00:01 PM: ❯ Context
10:00:01 PM:   production
10:00:01 PM: ​
10:00:01 PM: ❯ Using Next.js Runtime - v4.41.3
10:00:01 PM: ​
10:00:01 PM: ❯ Outdated plugins
10:00:01 PM:    - @netlify/plugin-nextjs@4.41.3: latest version is 5.12.1
10:00:01 PM:      To upgrade this plugin, please uninstall and re-install it from the Netlify plugins directory (https://app.netlify.com/plugins)
10:00:03 PM: Next.js cache restored.
10:00:03 PM: ​
10:00:03 PM: Build command from Netlify app                                
10:00:03 PM: ────────────────────────────────────────────────────────────────
10:00:03 PM: ​
10:00:03 PM: $ yarn run build
10:00:03 PM: yarn run v1.22.22
10:00:04 PM: $ next build
10:00:04 PM: Browserslist: caniuse-lite is outdated. Please run:
10:00:04 PM:   npx browserslist@latest --update-db
10:00:04 PM:   Why you should do it regularly: https://github.com/browserslist/browserslist#browsers-data-updating
10:00:04 PM: info  - Checking validity of types...
10:00:05 PM: Browserslist: caniuse-lite is outdated. Please run:
10:00:05 PM:   npx browserslist@latest --update-db
10:00:05 PM:   Why you should do it regularly: https://github.com/browserslist/browserslist#browsers-data-updating
10:00:05 PM: 
10:00:05 PM: Failed to compile.
10:00:05 PM: ./pages/blog/[slug].js
10:00:05 PM: 74:11  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: ./pages/blog/index.js
10:00:05 PM: 91:21  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: ./pages/resume.js
10:00:05 PM: 24:6  Warning: React Hook useEffect has a missing dependency: 'router'. Either include it or remove the dependency array.  react-hooks/exhaustive-deps
10:00:05 PM: ./components/Header/index.js
10:00:05 PM: 40:21  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: 40:21  Warning: img elements must have an alt prop, either with meaningful text, or an empty string for decorative images.  jsx-a11y/alt-text
10:00:05 PM: 50:19  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: 50:19  Warning: img elements must have an alt prop, either with meaningful text, or an empty string for decorative images.  jsx-a11y/alt-text
10:00:05 PM: 155:17  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: 155:17  Warning: img elements must have an alt prop, either with meaningful text, or an empty string for decorative images.  jsx-a11y/alt-text
10:00:05 PM: 185:17  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: 185:17  Warning: img elements must have an alt prop, either with meaningful text, or an empty string for decorative images.  jsx-a11y/alt-text
10:00:05 PM: ./components/Seo/index.js
10:00:05 PM: 56:6  Error: Unknown property 'crossorigin' found, use 'crossOrigin' instead  react/no-unknown-property
10:00:05 PM: ./components/WorkCard/index.js
10:00:05 PM: 13:9  Warning: Do not use <img>. Use Image from 'next/image' instead. See: https://nextjs.org/docs/messages/no-img-element  @next/next/no-img-element
10:00:05 PM: info  - Need to disable some ESLint rules? Learn more here: https://nextjs.org/docs/basic-features/eslint#disabling-rules
10:00:05 PM: error Command failed with exit code 1. (https://ntl.fyi/exit-code-1)
10:00:05 PM: info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
10:00:06 PM: Failed during stage 'building site': Build script returned non-zero exit code: 2 (https://ntl.fyi/exit-code-2)
10:00:06 PM: ​
10:00:06 PM: "build.command" failed                                        
10:00:06 PM: ────────────────────────────────────────────────────────────────
10:00:06 PM: ​
10:00:06 PM:   Error message
10:00:06 PM:   Command failed with exit code 1: yarn run build (https://ntl.fyi/exit-code-1)
10:00:06 PM: ​
10:00:06 PM:   Error location
10:00:06 PM:   In Build command from Netlify app:
10:00:06 PM:   yarn run build
10:00:06 PM: ​
10:00:06 PM:   Resolved config
10:00:06 PM:   build:
10:00:06 PM:     command: yarn run build
10:00:06 PM:     commandOrigin: ui
10:00:06 PM:     environment:
10:00:06 PM:       - NEXT_PRIVATE_TARGET
10:00:06 PM:     publish: /opt/build/repo/.next
10:00:06 PM:     publishOrigin: ui
10:00:06 PM:   plugins:
10:00:06 PM:     - inputs: {}
10:00:06 PM:       origin: ui
10:00:06 PM:       package: "@netlify/plugin-nextjs"
10:00:06 PM: Build failed due to a user error: Build script returned non-zero exit code: 2
10:00:06 PM: Failing build: Failed to build site
10:00:06 PM: Finished processing build request in 25.198s