# alerts
A repo to display Copado Robotic Testing alerts to the public.

- The `alerts.json` file is used to diplay the banner alers on the Copado Robotic Testing UI.
- The `title` is optional. If you don't wish to use it, leave the key in with the value as empty text.
- The `text` is required.

Example with both keys.
```
{
  "title": "Upcoming maintenance",
  "text": "Finland is on vacation. Let's close all bugs delete Azure DevOps."
}
```

Example with only the text.
```
{
  "title": "",
  "text": "Finland is on vacation. Let's close all bugs delete Azure DevOps."
}
```
