# JSON Utils

## Description

A helper for **format** or **compact** JSON from clipboard and then write to clipboard.

## Screenshot

![JSON Utils](https://raw.githubusercontent.com/cnfn/grocery/master/images/blog/bitbar_plugin_json_utils.png)

## Usage

### Format

1. Copy JSON string to clipboard, like `{"key": "value", "list": [1, 2]}`;

2. Click `JSON, Format`;

3. Paste to somewhere will get:

   ```json
   {
       "key": "value",
       "list": [
           1,
           2
       ]
   }
   ```

### Compact

1. Copy JSON string to clipboard, like:

   ```json
   {
       "key": "value",
       "list": [
           1,
           2
       ]
   }

   ```

2. Click `JSON, Compact`;

3. Paste to somewhere will get:

   ```json
   {"key":"value","list":[1,2]}

   ```