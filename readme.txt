# create and run project
npx create-next-app@latest cmnext-stock-app --typescript



# vscode extensions
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension vscode-icons-team.vscode-icons
code --install-extension naumovs.color-highlight
code --install-extension esbenp.prettier-vscode
code --install-extension humao.rest-client
code --install-extension riazxrazor.html-to-jsxc 
code --install-extension christian-kohler.path-intellisense
code --install-extension alexcvzz.vscode-sqlite

# add mui libs
yarn add @emotion/cache @emotion/react @emotion/server @emotion/styled
yarn add @mui/material
yarn add @mui/icons-material

# extra libs 1
yarn add formik formik-material-ui chart.js react-chartjs-2 react-moment moment react-number-format
yarn add @reduxjs/toolkit react-redux axios cookie @react-hook/debounce @mui/x-data-grid react-iframe
yarn add @types/cookie --dev