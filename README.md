# glencoe-desktop-releases
#Installers for the Glencoe Structural desktop app.


git pull
pnpm install
$env:GH_TOKEN = "<the token>"
pnpm --filter glencoe-desktop dist -- --publish always
