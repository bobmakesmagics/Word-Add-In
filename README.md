## Use Fluent UI React in Office Add-ins

Install the prerequisites
[Node.js](https://nodejs.org/) (the latest LTS version).

> Note: Office Add-ins should use HTTPS, not HTTP, even while you're developing. If you're prompted to install a certificate after you run one of the following > >
> commands, accept the prompt to install the certificate that the Yeoman generator provides. You may also have to run your command prompt or terminal as an  
> administrator for the changes to be made.

To test your add-in, run the following command in the root directory of your project. This starts the local web server and opens the Office host application with your add-in loaded.

```sh
npm start
```

To test your add-in in Office on the web, run the following command in the root directory of your project. When you run this command, the local web server starts. Replace "{url}" with the URL of a Word document on your OneDrive or a SharePoint library to which you have permissions.

```sh
npm run start:web -- --document {url}
```

That's all.

## License

MIT
