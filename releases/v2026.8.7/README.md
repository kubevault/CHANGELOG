# KubeVault v2026.8.7 (2026-08-07)


## [kubevault/apimachinery](https://github.com/kubevault/apimachinery)

### [v0.25.0](https://github.com/kubevault/apimachinery/releases/tag/v0.25.0)

- [599a2bed](https://github.com/kubevault/apimachinery/commit/599a2bed) chore(deps): go mod tidy && go mod vendor (#168)
- [1a0e4147](https://github.com/kubevault/apimachinery/commit/1a0e4147) Add Sigilr as an OpenBao-derivative Vault distro (#167)
- [4efa732f](https://github.com/kubevault/apimachinery/commit/4efa732f) Remove VaultRelay.spec.image; resolve it from the hub AppBinding's spec.version (#166)
- [a4f10f8d](https://github.com/kubevault/apimachinery/commit/a4f10f8d) Add Namespace Slice Helpers (#165)
- [9506b557](https://github.com/kubevault/apimachinery/commit/9506b557) Add tenant-namespace API for automatic OpenBao namespaces (#156)
- [ba64406c](https://github.com/kubevault/apimachinery/commit/ba64406c) Add spec.exposePrimary and the ClientTrafficPinned condition (#164)
- [aecac0c3](https://github.com/kubevault/apimachinery/commit/aecac0c3) Modernize golangci-lint config (#162)
- [0f322b76](https://github.com/kubevault/apimachinery/commit/0f322b76) Rename Vault Agent Leftovers (#161)
- [db14309e](https://github.com/kubevault/apimachinery/commit/db14309e) Use vr as shortname for VaultRelay
- [19e335e6](https://github.com/kubevault/apimachinery/commit/19e335e6) Rename VaultAgent CRD to VaultRelay (agent->relay) (#158)
- [c2df818e](https://github.com/kubevault/apimachinery/commit/c2df818e) Name the spoke kubernetes-auth role k8s-<cluster>-<vs> (#155)
- [e584cf38](https://github.com/kubevault/apimachinery/commit/e584cf38) Add VaultAgent and OCM agent placement API to VaultServer (#137)
- [b177c3ef](https://github.com/kubevault/apimachinery/commit/b177c3ef) Bump go.bytebuilders.dev/audit to v0.0.52 (#135)
- [50440b1b](https://github.com/kubevault/apimachinery/commit/50440b1b) Update go.bytebuilders.dev/audit to v0.0.51 (#134)
- [3b2e0d05](https://github.com/kubevault/apimachinery/commit/3b2e0d05) Add CLAUDE.md pointing to AGENTS.md
- [258f03b3](https://github.com/kubevault/apimachinery/commit/258f03b3) Fix release tracker workflow
- [d03a6c7c](https://github.com/kubevault/apimachinery/commit/d03a6c7c) Add AGENTS.md (#133)
- [075c9c56](https://github.com/kubevault/apimachinery/commit/075c9c56) Add 1gtm-app[bot] to kodiak auto_approve_usernames (#132)
- [3eac0dd1](https://github.com/kubevault/apimachinery/commit/3eac0dd1) Cleanup cves (#131)
- [a1a8b7b2](https://github.com/kubevault/apimachinery/commit/a1a8b7b2) Harden CI workflows (#130)
- [7e04d17f](https://github.com/kubevault/apimachinery/commit/7e04d17f) Configure dependabot refresh schedule (#128)



## [kubevault/cli](https://github.com/kubevault/cli)

### [v0.25.0](https://github.com/kubevault/cli/releases/tag/v0.25.0)

- [a64b70d8](https://github.com/kubevault/cli/commit/a64b70d8) Prepare for release v0.25.0 (#231)
- [f6bcff38](https://github.com/kubevault/cli/commit/f6bcff38) Clean up deps
- [5461dc81](https://github.com/kubevault/cli/commit/5461dc81) Prepare for release v0.25.0-rc.2 (#230)
- [7866f7d3](https://github.com/kubevault/cli/commit/7866f7d3) Modernize golangci-lint config (#229)
- [0f49286d](https://github.com/kubevault/cli/commit/0f49286d) Drop kubevault.dev/apimachinery/client dependency (#228)
- [3832c2fc](https://github.com/kubevault/cli/commit/3832c2fc) Add CLAUDE.md pointing to AGENTS.md
- [4839a579](https://github.com/kubevault/cli/commit/4839a579) Fix release tracker workflow
- [61d31fd8](https://github.com/kubevault/cli/commit/61d31fd8) Prepare for release v0.25.0-rc.1 (#227)
- [ca45ac56](https://github.com/kubevault/cli/commit/ca45ac56) Add AGENTS.md (#226)
- [4ed7b9d5](https://github.com/kubevault/cli/commit/4ed7b9d5) Harden CI workflows (#225)
- [b42d2b9b](https://github.com/kubevault/cli/commit/b42d2b9b) Prepare for release v0.25.0-rc.0 (#224)
- [c0234062](https://github.com/kubevault/cli/commit/c0234062) Cleanup cves (#223)
- [00b5938d](https://github.com/kubevault/cli/commit/00b5938d) Harden CI workflows (#222)
- [289a185b](https://github.com/kubevault/cli/commit/289a185b) Configure dependabot refresh schedule (#220)



## [kubevault/operator](https://github.com/kubevault/operator)

### [v0.25.0](https://github.com/kubevault/operator/releases/tag/v0.25.0)

- [fc6afdce](https://github.com/kubevault/operator/commit/fc6afdce9) Merge commit 'f63c2452e679487c11e6addd77f07e973c0aca5a' into release-0.25
- [f63c2452](https://github.com/kubevault/operator/commit/f63c2452e) Prepare for release v0.25.0 (#228)
- [d1338690](https://github.com/kubevault/operator/commit/d1338690b) Refactor Vault namespace/relay code and fix relay-image & migration correctness bugs (#224)
- [4402f8d6](https://github.com/kubevault/operator/commit/4402f8d6e) Support Sigilr as an OpenBao-derivative distribution (#227)
- [2fc4269c](https://github.com/kubevault/operator/commit/2fc4269ce) Resolve VaultRelay's container image from the hub AppBinding's spec.version (#225)
- [0e659db1](https://github.com/kubevault/operator/commit/0e659db1a) Ensure Namespace Slice CRD, Add ClusterID to Webhook (#223)
- [5b9c0ed9](https://github.com/kubevault/operator/commit/5b9c0ed90) Merge commit '2fcebcc9b329cba16769d030cd5e5bc666b35b75' into release-0.25
- [2fcebcc9](https://github.com/kubevault/operator/commit/2fcebcc9b) Prepare for release v0.25.0-rc.2 (#222)
- [6a93d458](https://github.com/kubevault/operator/commit/6a93d458d) Automatic OpenBao namespaces for KubeDB Platform tenants (#213)
- [1706fa88](https://github.com/kubevault/operator/commit/1706fa88e) design: tenant isolation on the OCM hub-spoke model (#214)
- [fe678460](https://github.com/kubevault/operator/commit/fe6784605) Pin client traffic to the Vault primary (spec.exposePrimary) (#220)
- [f76a2164](https://github.com/kubevault/operator/commit/f76a21646) Modernize golangci-lint config (#218)
- [400d7789](https://github.com/kubevault/operator/commit/400d7789f) Rename VaultAgent to VaultRelay; agentbackend -> relaybackend (agent->relay) (#217)
- [e3abfcbf](https://github.com/kubevault/operator/commit/e3abfcbf3) Remove nul file (#212)
- [11af4877](https://github.com/kubevault/operator/commit/11af48777) design: automatic OpenBao namespaces for KubeDB Platform tenants (#210)
- [b937d1d6](https://github.com/kubevault/operator/commit/b937d1d66) Fix errcheck lint: check fmt.Fprintf return in vault_test (#211)
- [8d8afcde](https://github.com/kubevault/operator/commit/8d8afcdeb) VaultAgent: hub-spoke deployment across OCM-managed clusters (#191)
- [8e259c10](https://github.com/kubevault/operator/commit/8e259c108) Fix e2e workflows (#190)
- [a09d5f2e](https://github.com/kubevault/operator/commit/a09d5f2ea) feat: Migrate operator to kubebuilder/controller-runtime style (#175)
- [83b7774f](https://github.com/kubevault/operator/commit/83b7774f0) Add CLAUDE.md pointing to AGENTS.md
- [3d90749d](https://github.com/kubevault/operator/commit/3d90749d1) Fix release tracker workflow
- [9418ad4b](https://github.com/kubevault/operator/commit/9418ad4b7) Fix release tracker workflow
- [593dd1ee](https://github.com/kubevault/operator/commit/593dd1ee6) Prepare for release v0.25.0-rc.1 (#174)
- [ecd00441](https://github.com/kubevault/operator/commit/ecd004413) Add AGENTS.md (#173)
- [eb6ba157](https://github.com/kubevault/operator/commit/eb6ba1574) Pin git user to 1gtm in update-crds/update-docs workflows (#172)
- [29418235](https://github.com/kubevault/operator/commit/294182359) Pin docker/login-action to v4.1.0 (#171)
- [545de7ef](https://github.com/kubevault/operator/commit/545de7ef7) Use docker/login-action instead of docker login command (#170)
- [402f21bc](https://github.com/kubevault/operator/commit/402f21bc4) Harden CI workflows (#169)
- [5a1522f2](https://github.com/kubevault/operator/commit/5a1522f26) Prepare for release v0.25.0-rc.0 (#168)
- [ae69e2d1](https://github.com/kubevault/operator/commit/ae69e2d1c) Cleanup cves (#167)
- [7c4b7a9a](https://github.com/kubevault/operator/commit/7c4b7a9a0) Harden CI workflows (#166)
- [eea0fa0c](https://github.com/kubevault/operator/commit/eea0fa0c7) Configure dependabot refresh schedule (#164)



## [kubevault/unsealer](https://github.com/kubevault/unsealer)

### [v0.25.0](https://github.com/kubevault/unsealer/releases/tag/v0.25.0)

- [bcce8ad3](https://github.com/kubevault/unsealer/commit/bcce8ad3) Cleanup deps
- [0f6a92ca](https://github.com/kubevault/unsealer/commit/0f6a92ca) Modernize golangci-lint config (#162)
- [d2717085](https://github.com/kubevault/unsealer/commit/d2717085) add namespace policy (#161)
- [a34e6891](https://github.com/kubevault/unsealer/commit/a34e6891) Grant policy-controller the relay/* backend paths (hub-spoke placement) (#160)
- [a7fe869a](https://github.com/kubevault/unsealer/commit/a7fe869a) Add CLAUDE.md pointing to AGENTS.md
- [3b5bf9c4](https://github.com/kubevault/unsealer/commit/3b5bf9c4) Fix release tracker workflow
- [aa6de2ae](https://github.com/kubevault/unsealer/commit/aa6de2ae) Add AGENTS.md (#158)
- [a7096a5a](https://github.com/kubevault/unsealer/commit/a7096a5a) Pin git user to 1gtm in update-crds/update-docs workflows (#157)
- [c92ce049](https://github.com/kubevault/unsealer/commit/c92ce049) Pin docker/login-action to v4.1.0 (#156)
- [97e4d369](https://github.com/kubevault/unsealer/commit/97e4d369) Add 1gtm-app[bot] to kodiak auto_approve_usernames (#155)
- [8dda08bf](https://github.com/kubevault/unsealer/commit/8dda08bf) Use docker/login-action instead of docker login command (#154)
- [50ce5684](https://github.com/kubevault/unsealer/commit/50ce5684) Normalize Prepare git user, fetch-depth, drop permission-issues (#153)
- [87ceec47](https://github.com/kubevault/unsealer/commit/87ceec47) Cleanup cves (#152)
- [5989ad61](https://github.com/kubevault/unsealer/commit/5989ad61) Use GitHub App token for release tracker comments (#151)
- [4f672af9](https://github.com/kubevault/unsealer/commit/4f672af9) Harden CI workflows (#150)
- [e283b0fb](https://github.com/kubevault/unsealer/commit/e283b0fb) Configure dependabot refresh schedule (#148)



