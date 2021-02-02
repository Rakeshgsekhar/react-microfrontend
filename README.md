Two repositories have been combined into one for the sake of simplicity of maintenance. Consider both the folders as two separate repositories.

Run yarn install inside mfa-application-frontend and mfa-common-frontend

Up the screen application, goto mfa-application-frontend and run:
lerna run dev --parallel --stream

Then, up the navbar in mfa-common-frontend, goto mfa-common-frontend and run:
lerna run dev --parallel --stream

Then, inside staying mfa-common-frontend itself, up the root config
lerna run root-dev --parallel --stream

