Run yarn install

Up the screen application, goto mfa-application-frontend and run:
lerna run dev --parallel --stream

Then, up the navbar in mfa-common-frontend, goto mfa-common-frontend and run:
lerna run dev --parallel --stream

Then, inside staying mfa-common-frontend itself, up the root config
lerna run root-dev --parallel --stream

