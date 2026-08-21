# openorca-fleet

GitOps manifest repo for OpenOrca-managed services — consumed by the `openorca-fleet`
ApplicationSet (Argo CD). Directory layout and full spec: see
[kit-fleet.md](https://github.com/daemon-blockint-tech/OpenOrca/blob/main/context/kits/kit-fleet.md)
in the main [OpenOrca](https://github.com/daemon-blockint-tech/OpenOrca) repo.

```
envs/
└── prod/
    ├── <service>/   # kustomize/helm manifests + Rollout (not Deployment)
    └── ...
```

Populated by SPEC task T10 (ApplicationSet + AppProject + notifications).
