# Add your own app

Instructions can be found in the [scoop documentation](https://github.com/lukesampson/scoop/wiki/Buckets#creating-your-own-bucket).

In summary, just make a JSON file named after your app with something like this:

```js
{
    "version": "0.3.0",
    "url": "https://github.com/ubclaunchpad/inertia/releases/download/v0.3.0/inertia.v0.3.0.windows.386.exe",
    "bin": "inertia.exe"
}
```

Then open up a pull request!
