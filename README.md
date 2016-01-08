# alfred-json-compressor
A python based Alfred workflow to compress and escape JSON.

Select some JSON, press **CTRL + SHIFT + J** and a compressed and escaped version of the JSON will be copied to your clipboard:

## Example

```JSON
{
   "width": 960,
   "height": 960
}
```

will be compressed to

```JSON
"{\"width\":960,\"height\":960}"
```
