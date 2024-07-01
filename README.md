# Repro for issue 7402

## Versions

firebase-tools: v13.12.0<br>
node: v20.12.2<br>
platform: Windows 10.0.19045.4529

## Steps to reproduce

1. Run `pnpm install`
1. Run `cd website`
1. Run `pnpm run build`
1. Run `cd ../`
1. Run `firebase deploy --only hosting --project PROJECT_ID`
1. Visit the website.
   - No errors were raised, website is rendered correctly
