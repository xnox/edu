---
date: 2023-02-14T01:25:23Z
title: "chainctl clusters profiles list"
slug: chainctl_clusters_profiles_list
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_clusters_profiles_list/
draft: false
images: []
type: "article"
toc: true
---
## chainctl clusters profiles list

List cluster profiles.

```
chainctl clusters profiles list [--output table|json|wide]
```

### Options

```
  -h, --help   help for list
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
```

### SEE ALSO

* [chainctl clusters profiles](/chainguard/chainguard-enforce/chainctl-docs/chainctl_clusters_profiles/)	 - Profile related commands.
