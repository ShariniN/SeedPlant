# SEED - Smart Plant Assistant (phone app)

A phone app for identifying plants from a photo, reading care guides, checking whether a spot suits a plant, and browsing agricultural services.

No server or install needed. It is a web app you add to your phone's home screen.

## Use it on your phone

1. Open the app link on your phone in Chrome (Android) or Safari (iPhone).
2. Paste your Pl@ntNet API key when asked, then tap **Save key**. The key is stored only on your phone.
3. Take or pick a photo, choose the plant part, and tap **Identify plant**.
4. To install it: Chrome menu > **Add to Home screen**, or Safari Share > **Add to Home Screen**.

Get a free key at https://my-api.plantnet.org/ (free tier: 500 identifications per day).

## Run it on a computer (optional)

Any static file server works. From this folder:

```
python -m http.server 8080
```

Then open http://localhost:8080. Plain http works on the computer; a phone needs the https link.

## Notes

- Your key is never written into the code. Do not commit a file containing it.
- The plant guide, placement check and services list work without a key.
- Services are sample listings for the demo.
