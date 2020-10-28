# Angular Browser (Chrome, Firefox, Edge) Extension Quickstart

Looking to build a chrome/firefox/edge extension with Angular? This project sets you up in under **5 minutes**.

## Installation

Clone the project to your local machine.

```bash
git clone bot101/angular-chrome-extension-quickstart.git
```

Run NPM install

```
npm i
```

Build project

```
npm run build
```

Once the project builds successfully, open Google Chrome's extension page
[chrome://extensions/](chrome://extensions/), enable developer mode, click on load unpacked and choose the generated `dist/` folder and you have a working chrome extension with live reload, testing setup, ngRx and husky set up to enable you to develop high-quality extensions!

## Usage

You can continue development as you would any angular project but are restricted by what is available to chrome/firefox extensions. All background code go to `background.ts`, options page content goes into the `OptionsComponent` and popup page content goes into `DashboardComponent`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
