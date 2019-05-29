# [Travelflan](https://www.travelflan.com/) chatbot widget usage sample for wwpkg

## Introduction

This repo demonstrated how to use integrate travelfaln chatbot in for wwpkg's website.

## Run demo
```bash
npm install
npm start
```
then open http://localhost:8080/ in your browser.


## Usage
add this script in the end of your website page.
```bash
<script src="https://widget.travelflan.com/loader/packagetour/dist/widget.packagetour.min.js"></script>
<script>
  window.TF_CHATBOT.init({
    environment: 'dev'  // please set value to 'production' if used in production env
  })
</script>
```
