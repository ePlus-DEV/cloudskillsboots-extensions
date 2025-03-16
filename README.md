<h1 align="center">
  <sub>
    <img src="https://github.com/ePlus-DEV/google-cloud-skills-boost-helper/blob/main/assets/icon.png" height="38" width="38">
  </sub>
  Google Cloud Skills Boost Helper
</h1>

***

<div align="center">
    <a href="https://chromewebstore.google.com/detail/lmbhjioadhcoebhgapaidogodllonbgg?utm_source=github">
        <img src="https://github.com/user-attachments/assets/4d8fd051-4c28-4290-afb8-9c182bb2b5d3" alt="Chrome Web Store">
    </a>
    <a href="https://addons.mozilla.org/addon/google-cloud-skills-boost-helper/?utm_source=github">
        <img src="https://github.com/user-attachments/assets/20177a18-81db-45ed-8838-64c29df48d34" alt="Firefox Add-ons">
    </a>
    <a href="https://addons.mozilla.org/addon/google-cloud-skills-boost-helper/?utm_source=github">
        <img src="https://github.com/user-attachments/assets/29994e96-2de9-4136-8f0e-b98c65c0cb28" alt="Microsoft Edge Add-ons">
    </a>
    <a href="https://addons.mozilla.org/addon/google-cloud-skills-boost-helper/?utm_source=github">
        <img src="https://github.com/user-attachments/assets/56481763-2d91-408d-8c45-eba77e2dc4c4" alt="Opera Add-ons">
    </a>
</div>

***

![postspark_export_2025-03-10_18-06-17](https://github.com/user-attachments/assets/2f157ec3-b7bf-4287-a0a2-ef13c3fc69b7)

```bash
pnpm dev
# or
npm run dev
```

Open your browser and load the appropriate development build. For example, if you are developing for the chrome browser, using manifest v3, use: `build/chrome-mv3-dev`.

You can start editing the popup by modifying `popup.tsx`. It should auto-update as you make changes. To add an options page, simply add a `options.tsx` file to the root of the project, with a react component default exported. Likewise to add a content page, add a `content.ts` file to the root of the project, importing some module and do some logic, then reload the extension on your browser.

For further guidance, [visit our Documentation](https://docs.plasmo.com/)

## Making production build

Run the following:

```bash
pnpm build
# or
npm run build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

## Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!
