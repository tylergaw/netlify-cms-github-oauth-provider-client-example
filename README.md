# NetlifyCMS GitHub OAuth Provider Client Example

**Blog post:**
[tylergaw.com/articles/netlify-cms-custom-oath-provider](https://tylergaw.com/articles/netlify-cms-custom-oath-provider)

A working example of a custom GitHub OAuth Provider for NetlifyCMS.

This is the client side. Where you log in to the NetlifyCMS.

The server side is available on Glitch:
[https://glitch.com/edit/#!/netlify-cms-github-oauth-provider-example](https://glitch.com/edit/#!/netlify-cms-github-oauth-provider-example)

### Configuration

Most of this example follows the [standard NetlifyCMS setup](https://www.netlifycms.org/docs/add-to-your-site/). A key to making this work is adding the `base_url` setting in [config.yml](admin/config.yml).

That tells NetlifyCMS where to look for the OAuth server.

```yml
backend:
  name: github
  branch: master
  repo: tylergaw/netlify-cms-github-oauth-provider-client-example # change this to your repo
  base_url: https://netlify-cms-github-oauth-provider-example.glitch.me # change this to your OAuth server
```
