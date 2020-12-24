# BerryResolutionIssue
An issue with yarn berry's package resolution

Just try running `yarn install && yarn dlx tailwindcss-cli@latest build -o tailwind.css` from the root and then look at `package.json` and you'll see the problem. 
