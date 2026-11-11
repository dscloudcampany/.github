<p align="center">
  <img src="https://raw.githubusercontent.com/dscloudcampany/.github/main/dscloud_github_banner.png" alt="DSCloud — PaaS Cloud Hosting" width="100%" />
</p>

<p align="center">
  <a href="https://dscloud.pt">Website</a> •
  <a href="https://docs.dscloud.pt">Documentation</a> •
  <a href="https://github.com/dscloudcampany/SdkApiJS">JavaScript SDK</a> •
  <a href="mailto:support@dscloud.pt">Support</a>
</p>

---

### Ecosystem

| Component | Stack | Description |
| :--- | :--- | :--- |
| **Core Platform** | `Node.js` · `Panel` | Git, ZIP, and CLI deployments with real-time logs and container controls |
| **JavaScript SDK** | [`SdkApiJS`](https://github.com/dscloudcampany/SdkApiJS) | Official `@dscloud/sdkapi` Node.js / TypeScript wrapper for the DSCloud REST API |
| **CLI & Tooling** | `CLI` · `GitHub Action` · `VS Code` | Automated deploys directly from your terminal, IDE, or CI/CD pipeline |
| **Multi-Language SDKs** | `Python` · `Go` | Native SDKs for integrating DSCloud infrastructure into backend workflows |

### Quickstart

```bash
npm install @dscloud/sdkapi
```

```ts
import { DsCloudAPIKEY } from "@dscloud/sdkapi";

const api = new DsCloudAPIKEY(process.env.DSCLOUD_API_KEY);
const app = api.getApplication("your-app-id");
```

---

<p align="center">
  <sub>Portugal · <a href="https://dscloud.pt">dscloud.pt</a> · <a href="mailto:support@dscloud.pt">support@dscloud.pt</a></sub>
</p>
