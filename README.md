# July Trip CPK Dashboard

Static GitHub Pages dashboard for July trip utilisation and contract CPK analysis.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `data.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

## CPK logic
`Contract CPK = Monthly Fixed Cost / Contracted KM per Month`

The trip source does not contain actual trip distance, so the dashboard maps contract CPK to trips by Contract ID. It does not represent actual trip cost divided by actual trip KM.
