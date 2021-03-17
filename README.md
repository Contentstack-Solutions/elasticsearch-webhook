# Elasticsearch webhook example
The following is an example of sending Contentstack Entries to Elasticsearch for indexing. The index is created on publish for an Entry/Locale pair. The index is deleted when an entry is unpublished or deleted, based on an Entry/Locale pair.

## Instructions

**Step 1**
```
$ npm install
```

**Step 2**
```
$ npm run
```
 
**Step 3**
```
$ ngrok http 3000
```

**Step 4**
Import `webhook.json` into Contentstack, and change the `URL to notify` to your ngrok address.