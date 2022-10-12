# Strips LoRa Translator TTN

This decoder is basically the same as the original payload decoder, with the exceptions of a few edits to fit the TTN format.

Please note that this version should only be used with The Things Network, for other Network Servers, we recommend https://gitlab.com/sensative/strips-lora-translator-open-source


<br>

## Install

1. Log in to your TTN console and click on the Application that contains your Strips
2. Click on the `Payload formatters` drop down list in the left menu
3. Select `Uplink`
4. Choose `Custom Javascript formater` under `Formatter type`
5. Paste the code the in the box named `Formatter code`
6. Press `Save changes`

<br>

## Troubleshooting

If the decodes does not work, go to the page of the end device and click on `Payload formatters`. Choose `Use application payload formatter` and then press `Saves changes`
