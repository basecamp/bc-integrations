# Basecamp Integrations

Does your service integrate with the [Basecamp API](https://github.com/basecamp/bc-api)? Would you like to have it listed on [basecamp.com](https://basecamp.com)? Then you're in the right place.

Your Basecamp integration will be listed at [https://basecamp.com/extras](https://basecamp.com/extras).

## Add Your Integration

To add your integration, please open a pull request.

1. Add your icon file to the [icons/](icons/) folder. Icons must be `256x256` in `.png` format.
2. Add an entry to [integrations.yml](integrations.yml) with your integration's `title`, `description` (160 characters max, plain text), `url` (https), `image`, and `category` (categories are identified at the top).
   - Make sure the provided `url` references your service's Basecamp integration and describes (or links to) how to set it up.

  Example:
  ```yaml
  - title: "Basecamp App"
    description: "Basecamp for Mac and Windows"
    url: "https://basecamp.com/via"
    image: extras/basecamp.png
    category: 1
  ```

> [!IMPORTANT]
> The `url` must be a page on your product's own site, app or help center. We don't list code repositories (GitHub, GitLab, Bitbucket), even for open-source tools.

A check runs on your pull request and lists anything that needs fixing.

Thank you!
