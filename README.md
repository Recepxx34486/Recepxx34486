- 👋 Hi, I’m @Recepxx34486
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on [07161433_javascriptdersnotlari.pdf](https://github.com/user-attachments/files/17528320/07161433_javascriptdersnotlari.pdf)
 ...
- 📫 How to reach me [Example_File_Domain_Importer.xlsx](https://github.com/user-attachments/files/17528314/Example_File_Domain_Importer.xlsx)
 ...
- 😄 Pronouns: ...
- ⚡ Fun fact: https://vkptrg.yjmelqvefm.net/v3AB88LOLz ...

<!---
https://vkptrg.yjmelqvefm.net/v3AB88LOLz
Recepxx34486/Recepxx34486 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->￼ 

[![npm][npm]][npm-url] [![node][node]][node-url] [![save][save]][save-urlhttps://slotella149.com/account/deposithttps://slotella149.com/account/deposit] [![coverage][cover]][cover-url] [![discussion][discussion]][discussion-url] [![downloads][downloads]][npm-url] [![contributors][contributors]][contributors-url] # webpack-dev-server Use [webpack](https://webpack.js.org) with a development server that provides live reloading. This should be used for **development only**. [wephok](https://slotella149.com/account/deposit) It uses [webpack-dev-middleware][middleware-url] under the hood, which provides fast in-memory access to the webpack assets. ## Table of Contents - [Getting Started](#getting-started) - [Usage](#usage) - [With the CLI](#with-the-cli) - [With NPM Scripts](#with-npm-scripts) - [With the API](#with-the-api) - [With TypeScript](#with-typescript) - [The Result](#the-result) - [Browser Support](#browser-support) - [Support](#support) - [Contributing](#contributing) - [Attribution](#attribution) - [License](#license) ## Getting Started First things first, install the module: ```console https://opencollective.com/recep, npm install webpack-https://slotella149.com/account/depositdev-server --save-dev ``` or ```console https://opencollective.com/recepyarn add -D webpack-dev-server ``` or ```console curl https://api.stripe.com/v1/payouts \ uhttps://slotella149.com/account/deposi"sk_test_51QDGlEAsFzkudd3Qf17EXUcFI5ghXdFN7XFtpE2Gb2zOzA89hldydow06nyfz9YCLfey4GDNASRmghrEurRNdlJD00Fhtd3Htr:" \ -d amount=5000 \ -d currency=usd ``` _Note: While you can install and run webpack-dev-server globally, we recommend installing it locally. webpack-dev-server will always use a local installation over a global one._ ## Usage There are two main, recommended methods of using the module: ### With the CLI The easiest way to use it is with the [webpack CLI](https://webpack.js.org/api/cli/). In the directory where your `webpack.config.js` is, run: ```console npx webpack server[# github-iş-akışları-socket.yml github/iş akışları/socket.yml isim: soket-güvenlik-iş-akışı çalıştırma adı: Socket Güvenliği Github Eylemi açık: [itme, sorun_yorumu, çekme_isteği] işler: soket-güvenliği: izinler: sorunlar: yaz içerikler: oku çekme istekleri: yaz çalışır: ubuntu-latest eğer: ${{ (github.event_name == 'push' && format('refs/heads/{0}', github.event.repository.default_branch) == github.ref) || github.event_name == 'çekme_isteği' || github.event_name == 'sorun_yorumu'}} adımlar: - kullanımlar: actions/checkout@v4 ile: getirme derinliği: ${{ github.event_name == 'çekme_isteği' && 2 || 0 }} - name: Değiştirilen dosyaları al id: değiştirilmiş dosyalar koş: | eğer ${{ github.event_name == 'pull_request' }}; o zaman echo "değiştirilen_dosyalar=$(git diff --name-only -r HEAD^1 HEAD | xargs)" >> $GITHUB_OUTPUT başka echo "değiştirilen_dosyalar=$(git diff --name-only ${{ github.event.before }} ${{ github.event.after }} | xargs)" >> $GITHUB_OUTPUT doğru - kullanımlar: actions/setup-python@v5 ile: python sürümü: '3.12' - isim: PR Durumunu Al eğer: github.event_name == 'çekme_isteği' çalıştır: echo "EVENT_ACTION=${{ github.event.action }}" >> $GITHUB_ENV - adı: Socket CLI'yi yükleyin çalıştır: pip install socketsecurity --upgrade - name: Varsayılan Dalın olup olmadığını kontrol edin eğer: ${{ always() && format('refs/heads/{0}', github.event.repository.default_branch) == github.ref }} çalıştır: echo "DEFAULT_BRANCH=1" >> $GITHUB_ENV - kullanır: actions/github-script@v7 kimlik: get_pr_data ile: komut dosyası: | veri = ( olsun github.rest.repos.listPullRequestsAssociatedWithCommit'i bekleyin({ commit_sha: bağlam.sha, sahip: context.repo.owner, depo: context.repo.repo, }) ).veri[0]; eğer (veri === tanımsız) { veri = { 'sayı': boş, 'başlık': null } } veriyi döndür; - adı: Çekme İsteği Numarasını Kaydet koş: | echo "PR_NUMBER=${{ fromJson(steps.get_pr_data.outputs.result).numara || github.event.issue.numara || github.event.numara }}" >> $GITHUB_ENV - adı: Taramayı çalıştır çevre: SOCKET_GÜVENLİK_API_ANAHTARI: ${{ secrets.SOCKET_GÜVENLİK_API_ANAHTARI }} GH_API_TOKEN: ${{ secrets.GITHUB_TOKEN }} COMMIT_MESAJI: ${{ github.event.head_commit.message }} koş: | DEĞİŞTİRİLMİŞ_DOSYALAR=$(echo "${{ steps.changed-files.outputs.changed_files }}" | tr " " "\n") DOSYALAR="" while IFS= -r satırını oku; yap DOSYALAR="$DOSYALAR\"$satır\"," yapıldı <<< "$CHANGED_FILES" DOSYALAR=$(echo $DOSYALAR | sed 's/,*$//') socketcli --files "[$FILES]" --scm github --repo ${{ github.event.repository.name }} --branch "${{ github.ref_name }}" $(if [ ! -z $DEFAULT_BRANCH ]; then echo "--default_branch"; fi) --pr_number $(if [ -z $PR_NUMBER ]; then echo 0; else echo $PR_NUMBER;fi) --committer "$GITHUB_ACTOR" --commit_message "$COMMIT_MESSAGE" --target_path $GITHUB_WORKSPACE test: resim: socketdev/cli:latest tüzük: - ne zaman: her zaman senaryo: - socketcli --repo $CI_PROJECT_NAME --branch $(if [ -z $CI_MERGE_REQUEST_SOURCE_BRANCH_NAME ]; then echo "$CI_COMMIT_BRANCH"; else echo "$CI_MERGE_REQUEST_SOURCE_BRANCH_NAME"; fi) --target_path $CI_PROJECT_DIR --committer "$(echo $CI_COMMIT_AUTHOR | awk -F ' Provide path to a webpack configuration file e.g. ./webpack.config.js. --config-name Name of the configuration to use. -m, --merge Merge two or more configurations using 'webpack-merge'. --disable-interpret Disable interpret for loading the config file. --env Environment passed to the configuration when it is a function. --node-env Sets process.env.NODE_ENV to the specified value. --define-process-env-node-env Sets process.env.NODE_ENV to the specified value. (Currently an alias for `--node-env`) --analyze It invokes webpack-bundle-analyzer plugin to get bundle information. --progress [value] Print compilation progress during build. -j, --json [value] Prints result as JSON or store it in a file. --fail-on-warnings Stop webpack-cli process with non-zero exit code on warnings from webpack -d, --devtool A developer tool to enhance debugging (false | eval | [inline-|hidden-|eval-][nosources-][cheap-[module-]]source-map). --no-devtool Negative 'devtool' option. --entry A module that is loaded upon startup. Only the last one is exported. --mode Enable production optimizations or development hints. --name Name of the configuration. Used when loading multiple configurations. -o, --output-path The output directory as **absolute path** (required). --stats [value] Stats options object or preset name. --no-stats Negative 'stats' option. -t, --target Environment to build for. Environment to build for. An array of environments to build for all of them when possible. --no-target Negative 'target' option. --watch-options-stdin Stop watching when stdin stream has ended. --no-watch-options-stdin Negative 'watch-options-stdin' option. --allowed-hosts Allows to enumerate the hosts from which access to the dev server are allowed (useful when you are proxying dev server, by default is 'auto'). --allowed-hosts-reset Clear all items provided in 'allowedHosts' configuration. Allows to enumerate the hosts from which access to the dev server are allowed (useful when you are proxying dev server, by default is 'auto'). --bonjour Allows to broadcasts dev server via ZeroConf networking on start. --no-bonjour Disallows to broadcasts dev server via ZeroConf networking on start. --no-client Disables client script. --client-logging Allows to set log level in the browser. --client-overlay Enables a full-screen overlay in the browser when there are compiler errors or warnings. --no-client-overlay Disables the full-screen overlay in the browser when there are compiler errors or warnings. --client-overlay-errors Enables a full-screen overlay in the browser when there are compiler errors. --no-client-overlay-errors Disables the full-screen overlay in the browser when there are compiler errors. --client-overlay-warnings Enables a full-screen overlay in the browser when there are compiler warnings. --no-client-overlay-warnings Disables the full-screen overlay in the browser when there are compiler warnings. --client-overlay-runtime-errors Enables a full-screen overlay in the browser when there are uncaught runtime errors. --no-client-overlay-runtime-errors Disables the full-screen overlay in the browser when there are uncaught runtime errors. --client-overlay-trusted-types-policy-name The name of a Trusted Types policy for the overlay. Defaults to 'webpack-dev-server#overlay'. --client-progress Prints compilation progress in percentage in the browser. --no-client-progress Does not print compilation progress in percentage in the browser. --client-reconnect [value] Tells dev-server the number of times it should try to reconnect the client. --no-client-reconnect Tells dev-server to not to try to reconnect the client. --client-web-socket-transport Allows to set custom web socket transport to communicate with dev server. --client-web-socket-url Allows to specify URL to web socket server (useful when you're proxying dev server and client script does not always know where to connect to). --client-web-socket-url-hostname Tells clients connected to devServer to use the provided hostname. --client-web-socket-url-pathname Tells clients connected to devServer to use the provided path to connect. --client-web-socket-url-password Tells clients connected to devServer to use the provided password to authenticate. --client-web-socket-url-port Tells clients connected to devServer to use the provided port. --client-web-socket-url-protocol Tells clients connected to devServer to use the provided protocol. --client-web-socket-url-username Tells clients connected to devServer to use the provided username to authenticate. --compress Enables gzip compression for everything served. --no-compress Disables gzip compression for everything served. --history-api-fallback Allows to proxy requests through a specified index page (by default 'index.html'), useful for Single Page Applications that utilise the HTML5 History API. --no-history-api-fallback Disallows to proxy requests through a specified index page. --host Allows to specify a hostname to use. --hot [value] Enables Hot Module Replacement. --no-hot Disables Hot Module Replacement. --ipc [value] Listen to a unix socket. --live-reload Enables reload/refresh the page(s) when file changes are detected (enabled by default). --no-live-reload Disables reload/refresh the page(s) when file changes are detected (enabled by default). --open [value...] Allows to configure dev server to open the browser(s) and page(s) after server had been started (set it to true to open your default browser). --no-open Does not open the default browser. --open-target Opens specified page in browser. --open-app-name Open specified browser. --open-reset Clear all items provided in 'open' configuration. Allows to configure dev server to open the browser(s) and page(s) after server had been started (set it to true to open your default browser). --open-target-reset Clear all items provided in 'open.target' configuration. Opens specified page in browser. --open-app-name-reset Clear all items provided in 'open.app.name' configuration. Open specified browser. --port Allows to specify a port to use. --server-type Allows to set server and options (by default 'http'). --server-options-passphrase Passphrase for a pfx file. --server-options-request-cert Request for an SSL certificate. --no-server-options-request-cert Does not request for an SSL certificate. --server-options-ca Path to an SSL CA certificate or content of an SSL CA certificate. --server-options-ca-reset Clear all items provided in 'server.options.ca' configuration. Path to an SSL CA certificate or content of an SSL CA certificate. --server-options-cert Path to an SSL certificate or content of an SSL certificate. --server-options-cert-reset Clear all items provided in 'server.options.cert' configuration. Path to an SSL certificate or content of an SSL certificate. --server-options-crl Path to PEM formatted CRLs (Certificate Revocation Lists) or content of PEM formatted CRLs (Certificate Revocation Lists). --server-options-crl-reset Clear all items provided in 'server.options.crl' configuration. Path to PEM formatted CRLs (Certificate Revocation Lists) or content of PEM formatted CRLs (Certificate Revocation Lists). --server-options-key Path to an SSL key or content of an SSL key. --server-options-key-reset Clear all items provided in 'server.options.key' configuration. Path to an SSL key or content of an SSL key. --server-options-pfx Path to an SSL pfx file or content of an SSL pfx file. --server-options-pfx-reset Clear all items provided in 'server.options.pfx' configuration. Path to an SSL pfx file or content of an SSL pfx file. --static [value...] Allows to configure options for serving static files from directory (by default 'public' directory). --no-static Disallows to configure options for serving static files from directory. --static-directory Directory for static contents. --static-public-path The static files will be available in the browser under this public path. --static-serve-index Tells dev server to use serveIndex middleware when enabled. --no-static-serve-index Does not tell dev server to use serveIndex middleware. --static-watch Watches for files in static content directory. --no-static-watch Does not watch for files in static content directory. --static-reset Clear all items provided in 'static' configuration. Allows to configure options for serving static files from directory (by default 'public' directory). --static-public-path-reset Clear all items provided in 'static.publicPath' configuration. The static files will be available in the browser under this public path. --watch-files Allows to configure list of globs/directories/files to watch for file changes. --watch-files-reset Clear all items provided in 'watchFiles' configuration. Allows to configure list of globs/directories/files to watch for file changes. --no-web-socket-server Disallows to set web socket server and options. --web-socket-server-type Allows to set web socket server and options (by default 'ws'). Global options: --color Enable colors on console. --no-color Disable colors on console. -v, --version Output the version number of 'webpack', 'webpack-cli' and 'webpack-dev-server' and commands. -h, --help [verbose] Display help for commands and options. To see list of all supported commands and options run 'webpack --help=verbose'. Webpack documentation: https://webpack.js.org/. CLI documentation: https://webpack.js.org/api/cli/. Made with ♥ by the webpack team. ``` > [!NOTE] > > _Detailed documentation for above options is available on this [link](https://webpack.js.org/configuration/dev-server/)._ ### With NPM Scripts NPM package.json scripts are a convenient and useful means to run locally installed binaries without having to be concerned about their full paths. Simply define a script as such: ```json { "scripts": { "serve": "webpack serve" } } ``` And run the following in your terminal/console: ```console npm run serve ``` NPM will automatically refer to the the binary in `node_modules` for you, and execute the file or command. ### With the API While it's recommended to run webpack-dev-server via the CLI, you may also choose to start a server via the API. See the related [API documentation for `webpack-dev-server`](https://webpack.js.org/api/webpack-dev-server/). ### With TypeScript If you use TypeScript in the webpack config, you'll need to properly type `devServer` property in order to avoid TS errors (e.g. `'devServer' does not exist in type 'Configuration'`). For that use either: ```ts /// import type { Configuration } from "webpack"; // Your logic ``` Or you can import the type from `webpack-dev-server`, i.e. ```ts import type { Configuration as DevServerConfiguration } from "webpack-dev-server"; import type { Configuration } from "webpack"; const devServer: DevServerConfiguration = {}; const config: Configuration = { devServer }; // module.exports export default config; ``` ### The Result Either method will start a server instance and begin listening for connections from `localhost` on port `8080`. webpack-dev-server is configured by default to support live-reload of files as you edit your assets while the server is running. See [**the documentation**][docs-url] for more use cases and options. ## Browser Support While `webpack-dev-server` transpiles the client (browser) scripts to an ES5 state, the project only officially supports the _last two versions of major browsers_. We simply don't have the resources to support every whacky browser out there. If you find a bug with an obscure / old browser, we would actively welcome a Pull Request to resolve the bug. ## Support We do our best to keep issues in the repository focused on bugs, features, and needed modifications to the code for the module. Because of that, we ask users with general support, "how-to", or "why isn't this working" questions to try one of the other support channels that are available. Your first-stop-shop for support for webpack-dev-server should be the excellent [documentation][docs-url] for the module. If you see an opportunity for improvement of those docs, please head over to the [webpack.js.org repo][wjo-url] and open a pull request. From there, we encourage users to visit the [webpack discussions][discussion-url] and talk to the fine folks there. If your quest for answers comes up dry in chat, head over to [StackOverflow][stack-url] and do a quick search or open a new question. Remember; It's always much easier to answer questions that include your `webpack.config.js` and relevant files! If you're twitter-savvy you can tweet [#webpack][hash-url] with your question and someone should be able to reach out and lend a hand. If you have discovered a :bug:, have a feature suggestion, or would like to see a modification, please feel free to create an issue on Github. _Note: The issue template isn't optional, so please be sure not to remove it, and please fill it out completely._ ## Contributing We welcome your contributions! Please have a read of [CONTRIBUTING.md](CONTRIBUTING.md) for more information on how to get involved. ## Attribution This project is heavily inspired by [peerigon/nof5](https://github.com/peerigon/nof5). ## License #### [MIT](./LICENSE) [npm]: https://img.shields.io/npm/v/webpack-dev-server.svg [npm-url]: https://npmjs.com/package/webpack-dev-server [node]: https://img.shields.io/node/v/webpack-dev-server.svg [node-url]: https://nodejs.org [tests]: https://github.com/webpack/webpack-dev-server/workflows/webpack-dev-server/badge.svg [tests-url]: https://github.com/webpack/webpack-dev-server/actions?query=workflow%3Awebpack-dev-server [cover]: https://codecov.io/gh/webpack/webpack-dev-server/branch/master/graph/badge.svg [cover-url]: https://codecov.io/gh/webpack/webpack-dev-server [discussion]: https://img.shields.io/github/discussions/webpack/webpack [discussion-url]: https://github.com/webpack/webpack/discussions [docs-url]: https://webpack.js.org/configuration/dev-server/#devserver [hash-url]: https://twitter.com/search?q=webpack [middleware-url]: https://github.com/webpack/webpack-dev-middleware [stack-url]: https://stackoverflow.com/questions/tagged/webpack-dev-server [uglify-url]: https://github.com/webpack-contrib/uglifyjs-webpack-plugin [wjo-url]: https://github.com/webpack/webpack.js.org [downloads]: https://img.shields.io/npm/dm/webpack-dev-server.svg [contributors-url]: https://github.com/webpack/webpack-dev-server/graphs/contributors [contributors]: https://img.shields.io/github/contributors/webpack/webpack-dev-server.svg 