# BranchTrack Cloudflare Error Pages

Custom BranchTrack-branded error pages for Cloudflare 500 class errors:

- [**Cloudflare Custom Pages**](https://support.cloudflare.com/hc/en-us/articles/200172706-Configuring-Custom-Pages-Error-and-Challenge-)

Cloudflare uses a wide range of error codes to identify issues in handling request traffic. By default, these error pages mention Cloudflare; however, custom error pages help you provide a consistent brand experience for your users. 

If you are on the Pro, Business, or Enterprise plan you can customize and brand these pages for your whole account or for specific domains. You can design custom error pages to appear during a security challenge or when an error occurs.

```
500, 501, 503, and 505 responses do not trigger custom error pages to avoid breaking specific API endpoints and other web applications.
```

Alternatively, Enterprise customers can customize 5XX error pages at their origin via Enable Origin Error Pages in the Custom Pages app in the dashboard..

```
Enable Origin Error Pages excludes 521 and 522 errors.
```
