# How to update the website

Target url : https://nicolasboeuf.fr/carbon-pledges/

## Update chart settings

From here, you can change pledges color and description as well as the list of countries.

To update the datavizualisations settings, click on the config.json at the root of the repository file and then on "Edit file".

Make your modifications and then click on "Commit changes".

Make sure that "Commit directly to the master branch" is selected and click on "Commit changes".

## Update data

Each chart in the website have his own data folder here.

To update one chart's dataset, click on the folder corresponding.

When your are on the page displaying the files list, click on "Add file" and select "Upload file".

Drag and drop the new files

Make sure that "Commit directly to the master branch" is selected and click on "Commit changes".

## HTML in texts

In order to add a line-break in texts, use a double tag such as : `<br><br>`

In order to add a link in texts, use a link tag as such (please use single quote in the href attribute) : `<a href='http://mylink.com'>Text of the link</a>`

## Troubleshooting

If you have any doubt or one change is not working, please copy-paste the json file here : https://jsonlint.com/
Click on validate json and copy-paste the result in github
