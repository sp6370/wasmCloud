# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.11.0 (2025-05-28)

### Chore

 - <csr-id-7df6305aac78635e26e478992509bb07915868d9/> bump versions
 - <csr-id-915c124e2907cb5dcfc4c1a6fbbf328b0ae2ade3/> Address clippy feedback
 - <csr-id-13d312c5dc7dbd450a64fe98f3df01db3d5df6d0/> Rename wasmcloud:identity@0.1.0-draft to wasmcloud:identity@0.0.1
 - <csr-id-3078c88f0ebed96027e20997bccc1c125583fad4/> bump provider-archive v0.16.0, wasmcloud-core v0.17.0, wasmcloud-tracing v0.13.0, wasmcloud-provider-sdk v0.14.0, wasmcloud-provider-http-server v0.27.0, wasmcloud-provider-messaging-nats v0.26.0, wasmcloud-runtime v0.9.0, wasmcloud-secrets-types v0.6.0, wasmcloud-secrets-client v0.7.0, wasmcloud-host v0.25.0, wasmcloud-test-util v0.17.0, secrets-nats-kv v0.2.0, wash v0.41.0
 - <csr-id-3b45c855936a73ae588c77b0932647f25946cff5/> bump for 0.8.1 release
 - <csr-id-98bf9ae36fc321fc7803a7485f32b833907f036e/> address clippy warnings
 - <csr-id-4f30198215220b3f9ce0c2aa6da8aa7d31a6a72d/> bump wasmcloud-core v0.16.0, wash-lib v0.32.0, wash-cli v0.38.0, safety bump 6 crates
   SAFETY BUMP: wash-lib v0.32.0, wash-cli v0.38.0, wasmcloud-host v0.24.0, wasmcloud-provider-sdk v0.13.0, wasmcloud-test-util v0.16.0, wasmcloud-runtime v0.8.0
 - <csr-id-e71198a83c32dcce51f2e7e7a3a8fb953899c82a/> address clippy warnings
 - <csr-id-e286c285df542d818489c934d03ceedcf5f4135a/> attach OTEL context
 - <csr-id-b7bdfed2f043c6fbcf17ef6588c6b099057014a2/> add `wasmcloud:messaging@0.3.0` dependency
 - <csr-id-eb52eca817fe24b33e7f1a65c1ba5c46c50bef4e/> removed unused dependencies
   A batch scanning all crates and remove unused dependencies by running 'cargo machete'.
 - <csr-id-68ea303e2cb3a3bbfd6878bcc1884f4951ed693d/> convert wasi-logging levels into more conventional format
 - <csr-id-c5ba85cfe6ad63227445b0a5e21d58a8f3e15e33/> bump wascap v0.15.1, wasmcloud-core v0.13.0, wash-lib v0.29.0, wasmcloud-tracing v0.10.0, wasmcloud-provider-sdk v0.11.0, wash-cli v0.36.0, safety bump 7 crates
   SAFETY BUMP: wash-lib v0.29.0, wasmcloud-tracing v0.10.0, wasmcloud-provider-sdk v0.11.0, wash-cli v0.36.0, wasmcloud-host v0.22.0, wasmcloud-runtime v0.6.0, wasmcloud-test-util v0.14.0
 - <csr-id-44bf4c8793b3989aebbbc28c2f2ce3ebbd4d6a0a/> bump wasmcloud-core v0.12.0, wash-lib v0.28.0, wasmcloud-tracing v0.9.0, wasmcloud-provider-sdk v0.10.0, wash-cli v0.35.0, safety bump 7 crates
   SAFETY BUMP: wash-lib v0.28.0, wasmcloud-tracing v0.9.0, wasmcloud-provider-sdk v0.10.0, wash-cli v0.35.0, wasmcloud-host v0.21.0, wasmcloud-runtime v0.5.0, wasmcloud-test-util v0.13.0
 - <csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/> allow complex types
 - <csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/> update component/runtime/host crate READMEs
 - <csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/> increase max memory size to 10mb
   This commit increases the max memory that can be addressed by a single
   component to 10mb.
 - <csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/> update wRPC
 - <csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/> remove unused logging exports
 - <csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/> address clippy warnings
 - <csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/> update to stream-based serving
 - <csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/> Replace actor reference by component in runtime crate
 - <csr-id-e7c30405302fcccc612209335179f0bc47d8e996/> improve error messages for missing links
   When known interfaces are accessed, we show a message that notes that
   the target is unknown, but we can improve on that by alerting the user
   to a possibly missing link.
 - <csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/> Replace actor references by component in crates
   Rename wash-cli wash-build tests name and references
   
   Fix nix flake path to Cargo.lock file
   
   Fix format
   
   Rename in wash-cli tests
 - <csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/> generate changelogs after 1.0.1 release
 - <csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/> updated with newest features
 - <csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/> replace references to 'actor' with 'component'
 - <csr-id-955a6893792e86292883e76de57434616c28d380/> update `messaging` to `0.2.0`
 - <csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/> reenable `clippy::pedantic`
 - <csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/> remove unused dependencies
 - <csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/> remove compat crate
 - <csr-id-5e4572379d370de74dad4b393746fee242e374f2/> update WIT dependencies
 - <csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/> move CallTargetInterface to core
 - <csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/> simplify error handling
 - <csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/> fix clippy lints
 - <csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/> integrate set-link-name and wrpc
 - <csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/> remove `Actor` abstraction
 - <csr-id-22e71e59be566136f6028393153827662ec9f68e/> import `wrpc-runtime-wasmtime`
 - <csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/> remove `wit-component` dep
   Ciao
 - <csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/> appease Clippy
   Chillax, Clip
 - <csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/> switch wasi-keyvalue to `main`
 - <csr-id-089b8955d309b1cab3eaa45f03d394656deada55/> fix `wasi-keyvalue` incoming value ownership mismatch
 - <csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/> implement preview 2 interfaces
 - <csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/> update WIT packages
 - <csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/> remove logging `with` pin
 - <csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/> update to Wasmtime 15
 - <csr-id-2389f27f0b570164a895a37abd462be2d68f20be/> polish tracing and logging levels
 - <csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/> integrate `wash` into the workspace
 - <csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/> update to Wasmtime 14 and latest WIT
 - <csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/> resolve 1.73.0 warnings
 - <csr-id-0023f7e86d5a40a534f623b7220743f27871549e/> reduce verbosity of instrumented functions
 - <csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/> mark non-exhaustive Debug impls as such
 - <csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/> remove noisy fields from instruments

### New Features

 - <csr-id-745cf8152e0403d59d0897e4edf540c15ac2867c/> allow configurable core instances per component
 - <csr-id-6061eabcd60c56de88ed275aa1b988afec9a426a/> add `wasmcloud:bus/error.error`
 - <csr-id-2c167ec361f35ac469a087d32a671813a11e0b71/> update wrpc and wasmtime
 - <csr-id-e9e32ced1cdc7d00e13bd268ddb78388fb03d1a0/> Add wasmcloud:identity interface for fetching component workload identity
 - <csr-id-3147765c1955119d54df26600738b8963abc792d/> update redis:keyvalue:watch configuration to be configurable by link config
 - <csr-id-ca530c77e94d755f3e4dff9e7d486dd6b1f7c2e7/> add wasi:keyvalue/watch handler and redis provider
 - <csr-id-c20d617710a8e9d82a1b5549d7dfaf7b1288f85a/> fully support WASI >0.2.2
 - <csr-id-febf47d0ed7d70a245006710960a1a3bd695e6bf/> gate messaging@v3 behind feature flag
 - <csr-id-8afa8ff95db21c93d3b280edc39d477dc8a2aaac/> implement `wasmcloud:messaging@0.3.0`
 - <csr-id-9adf2b51b2e2c416c1b62040fc34e4e8a319b7a2/> Enable memory_init_cow in wasmtime
 - <csr-id-d1feac0b8abb8cb8e2eec665b4d9b38ec8cd6d7f/> propagate outgoing context via store not handler
 - <csr-id-45fa6b06216da820045e4d39838a6ac3bdf97075/> add builtin `wasmcloud:messaging`, HTTP server
 - <csr-id-a7015f83af4d8d46284d3f49398ffa22876f290d/> add lattice@1.0.0 and @2.0.0 implementations
 - <csr-id-b8c2b999c979cd82f6772f3f98ec1d16c7f5565d/> add support for WASI 0.2.2
 - <csr-id-5095c22d266331cecdeacc0d29b0a4d08f5ab258/> Adds support for versioned wasi logging interface
   This brings in the new versioned wasi logging dependency and adds it to
   the host's default exports. This also maintains support for the unversioned
   logging as well.
   
   Please note that I did not update the component crate as it should still
   work and its current deps can't be updated from the runtime crate. I did
   manually test this and will have more tests in the next commit with
   upgrading dependencies
 - <csr-id-f5093226a252c35be1ea1e9ed9740923f33ec015/> update to WASI 0.2.1
 - <csr-id-c37c92abf8c93a40f8174c588e83b5242dcbc4c5/> update to wasmtime 25
 - <csr-id-8575f732df33ca973ff340fc3e4bc7fbfeaf89f3/> Adds support for batch support to the host
   This enables keyvalue batch support inside of the host, along with a test
   to make sure it works. Not all of our providers implement batch yet, so
   this uses the Redis provider, which did have implementions. I did have to
   fix the redis provider to get the right type of data back and transform
   it. I also had to update our wRPC versions so we could pick up on some
   bug fixes for the types we are encoding in the batch interface.
 - <csr-id-056b57e50cfc13ecd863f54d30032988bd23d94b/> enable wasmtime gc feature
 - <csr-id-26d7f64659dbf3263f36da92df89003c579077cc/> fallback to `wrpc:blobstore@0.1.0`
 - <csr-id-156d3f39e6775ec6aea3a1eb864bf7c893749e07/> update to Wasmtime 23
 - <csr-id-070751231e5bb4891b995e992e5206b3050ecc30/> pass original component instance through the context
 - <csr-id-9cb1b784fe7a8892d73bdb40d1172b1879fcd932/> upgrade `wrpc`, `async-nats`, `wasmtime`
 - <csr-id-a5f9432845bcb7c8f423776fd56ef4a735fe43c7/> add `TargetEntity::lattice_id()`
 - <csr-id-077a28a6567a436c99368c7eb1bd5dd2a6bc6103/> gracefully shutdown epoch interrupt thread
 - <csr-id-f986e39450676dc598b92f13cb6e52b9c3200c0b/> generate crate changelogs
 - <csr-id-3eb453405aa144599f43bbaf56197566c9f0cf0a/> count epoch in a separate OS thread
 - <csr-id-a66921edd9be3202d1296a165c34faf597b1dec1/> propagate `max_execution_time` to the runtime
 - <csr-id-e928020fd774abcc213fec560d89f128464da319/> limit max execution time to 10 minutes
 - <csr-id-33b50c2d258ca9744ed65b153a6580f893172e0c/> update to Wasmtime 20
 - <csr-id-9cd2b4034f8d5688ce250429dc14120eaf61b483/> update `wrpc:keyvalue` in providers
   part of this process is adopting `wit-bindgen-wrpc` in the host
 - <csr-id-a1754195fca5a13c8cdde713dad3e1a9765adaf5/> update `wasi:keyvalue`
 - <csr-id-2352092930b50992e47e7fcf013ae5f084bf2a8e/> Bumps our wasmcloud wit to 1.0
   This bumps our main `wasmcloud:bus` package and the package in the `runtime`
   crate to 1.0.0 in preparation for release. Also removes the use of
   the wasmcloud interface in tests where it wasn't needed
 - <csr-id-023358b41b154e75a737f10f652e197dfa6b0093/> update to wasmtime 19
 - <csr-id-f56492ac6b5e6f1274a1f11b061c42cace372122/> migrate to `wrpc:keyvalue`
 - <csr-id-383b3f3067dddc913d5a0c052f7bbb9c47fe8663/> implement `wrpc:blobstore/blobstore` for FS
 - <csr-id-614af7e3ed734c56b27cd1d2aacb0789a85e8b81/> implement Redis `wrpc:keyvalue/{atomic,eventual}`
 - <csr-id-e0dac9de4d3a74424e3138971753db9da143db5a/> implement `wasi:http/outgoing-handler` provider
 - <csr-id-0c5aee7621f01f6a3a90322c55836f45184df79a/> support p1 module execution
 - <csr-id-76c1ed7b5c49152aabd83d27f0b8955d7f874864/> support pubsub on wRPC subjects
   Up until now, publishing and subscribing for RPC communcations on the
   NATS cluster happened on subjects that were related to the wasmbus
   protocol (i.e. 'wasmbus.rpc.*').
   
   To support the WIT-native invocations, i.e. wRPC (#1389), we must
   change the publication and subscription subjects to include also the
   subjects that are expected to be used by wprc.
   
   This commit updates the provider-sdk to listen *additionally* to
   subjects that are required/used by wrpc, though we do not yet have an
   implementation for encode/deocde.
 - <csr-id-590a49477d5832ec99f3b2e251813d51b4abb274/> Switches runtime config to use a pooling allocator
   This leads to significant performance increases on Linux and brings it
   up to the same performance levels as other operating systems
 - <csr-id-400802ac767a06459fc1d93c3ab5cd4223e8506f/> improve byte stream efficiency
 - <csr-id-25e3e51d7e123aae3e3681886d2e095b29202b94/> Switches modules to use pre instantiation instead
   In my load testing of this locally, this led to a 20% increase in throughput
 - <csr-id-f2223a3f5378c3cebfec96b5322df619fcecc556/> implement `wrpc:http/incoming-handler`
 - <csr-id-0c0c004bafb60323018fc1c86cb13493f72d29cd/> switch to `wrpc` for `wasmcloud:messaging`
 - <csr-id-5ede01b1fe0bc62234d2b7d6c72775d9e248a130/> switch to `wrpc:{keyvalue,blobstore}`
 - <csr-id-246384524cfe65ce6742558425b885247b461c5c/> implement `wrpc:http/outgoing-handler.handle`
 - <csr-id-5d19ba16a98dca9439628e8449309ccaa763ab10/> change set-target to set-link-name
   Up until the relatively low-level `wasmcloud:bus/lattice` WIT
   interface has used a function called `set-target` to aim invocations
   that occurred in compliant actors and providers.
   
   Since wRPC (#1389)
   enabled  wasmCloud 1.0 is going to be WIT-first going forward, all
   WIT-driven function executions have access to the relevant
   interface (WIT interfaces, rather than Smithy-derived ones) that they
   call, at call time.
   
   Given that actor & provider side function executions have access to
   their WIT interfaces (ex. `wasi:keyvalue/readwrite.get`), what we need
   to do is differentiate between the case where *multiple targets*
   might be responding to the same WIT interface-backed invocations.
   
   Unlike before, `set-target` only needs to really differentiate between *link
   names*.
   
   This commit updates `set-target` to perform differentiate between link
   names, building on the work already done to introduce more opaque
   targeting via Component IDs.
 - <csr-id-5d1590e231f75e4d418a5115b3449dda0dadec9a/> record polyfilled component imports
 - <csr-id-18875a7264ec4b8c0a82f3389be72267be202e58/> fix custom interface support and tests
 - <csr-id-fec6f5f1372a1de5737f5ec585ad735e14c20480/> remove module support
 - <csr-id-219342386861f21fab64429cad4f8e88ae679c0a/> add resource handling stubs
 - <csr-id-eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a/> support composite types
 - <csr-id-da6e2b3a91013c8564c22f8305d665aec78a072d/> support composite Wasmtime type reflection in polyfills
 - <csr-id-713e7746a9aa61ceff373cf62cf85e68617fa788/> add (most of) custom interface plumbing
 - <csr-id-64d21b1f3d413e4c5da78d8045c1366c3782a190/> Adds some additional context around test failures I was seeing
 - <csr-id-1a048a71320dbbf58f331e7e958f4b1cd5ed4537/> Adds support for actor config
   This is a fairly large PR because it is adding several new control interface
   topics as well as actually adding the actor config feature.
   
   This feature was motivated by 2 major reasons:
   
   1. We have been needing something like this for a while, at the very least for
      being able to configure link names in an actor at runtime
   2. There aren't currently any active (yes there were some in the past) efforts
      to add a generic `wasi:cloud/guest-config` interface that can allow any host
      to provide config values to a component. I want to use this as a springboard
      for the conversation in wasi-cloud as we will start to use it and can give
      active feedback as to how the interface should be shaped
   
   With that said, note that this is only going to be added for actors built against
   the component model. Since this is net new functionality, I didn't think it was
   worth it to try to backport.
   
   As for testing, I have tested that an actor can import the functions and get the values
   via the various e2e tests and also manually validated that all of the new topics
   work.
 - <csr-id-cfb66f81180a3b47d6e7df1a444a1ec945115b15/> implement wasifills for simple types
 - <csr-id-2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3/> implement outgoing HTTP
 - <csr-id-123cb2f9b8981c37bc333fece71c009ce875e30f/> add support for call aliases
 - <csr-id-813ce52a9c11270814eec051dfaa8817bf9f567d/> support chunking and dechunking of requests
 - <csr-id-bef159ab4d5ce6ba73e7c3465110c2990da64eac/> implement `wasi:blobstore`
 - <csr-id-d434e148620d394856246ac34bb0a64c37181970/> partially implement `wasi:keyvalue/atomic`
 - <csr-id-50d0ed1086c5f417ed64dcce139cc3c2b50ca14c/> implement `wasmcloud:http/incoming-handler` support
 - <csr-id-54f0afa7b7d67b658113eb2a7ea667b77ea4bd55/> move builtin smithy structs to `compat`
 - <csr-id-2e3bd2bd7611e5de9fe123f53778f282613eb0de/> implement link names and a2a calls
 - <csr-id-77d663d3e1fd5590177ac8003a313a3edf29ab1f/> implement `wasmcloud:messaging/consumer` support
 - <csr-id-02c1ddc0d62b40f63afe4d270643ebc3bf39c081/> implement `wasi:keyvalue/readwrite` support
 - <csr-id-9eda090fe6d790f239093738515570a7886eae8d/> introduce Blobstore trait
 - <csr-id-4de853a1d3e28126faf9efa51aaa97714af7b493/> implement actor -> provider linking
 - <csr-id-3ae7cce621b4be163feac7be903f3ff66f40ddc3/> provide wasmCloud interface stubs
 - <csr-id-e943eca7512a0d96a617451e2e2af78718d0f685/> implement linkdef add/delete
 - <csr-id-7364dd8afae5c8884ca923b39c5680c60d8d0e3d/> implement data streaming
   - make claims optional (at least for now)
   - add streaming support to `wasmcloud:bus`
   - rename `wasmcloud_host` -> `wasmcloud_runtime`
   - remove all `wasmcloud-interface-*` usages
   - add support for `command` executables (I/O actors)
   - add local lattice proving the concept, which is used for testing of the feature
   - implement an actor instance pool

### Bug Fixes

 - <csr-id-aff0539e8e707f88906630b6c33252671be8c97d/> extract suffix from version not name
 - <csr-id-7413aeb39e7f3b2e7550cdefafe982d6ffbe2da6/> connect function trace to context
 - <csr-id-c5c6be96a3fe6dd3b7264ed7acf6b105404652be/> propagate serve trace into handlers
 - <csr-id-44e1d0ef5acd63fbb08f5887557d39ce74680378/> end epoch interruption, don't await
 - <csr-id-4da0105ac7bf463eeb79bc3047cb5e92664f8a7c/> rework `wasi:http` error handling
 - <csr-id-853105c8ad06b92686589b669765bbdbd439ccbc/> Ensures we have the proper limits set for max components
   It turns out that there are a bunch of other settings that we could have
   hit the limit on that we needed to set. These new settings are all set
   to the same as max components because you could have that number of
   individual components that would each have their own core module and
   stack.
   
   I tested this under load to make sure it actually works
 - <csr-id-726dd689e6d64eb44930834425d69f21cefc61cd/> log handling errors
 - <csr-id-8f0e15e01732e873e5861b1336254e21eafa0f10/> additional static instances
 - <csr-id-b014263cf3614995f597336bb40e51ab72bfa1c9/> setup debug traces
   This commit contains experimental code used to debug/replicate the
   o11y traces for making a call with http-client & http-provider.
   
   Running this requires the following hackery:
   
   - running the docker compose for o11y
   - (re) building dog-fetcher
   - modifying the WADM w/ dog fetcher (done by this commit)
   - build & create PAR for http-client
   - build & create PAR for http-server
   - set WASMCLOUD_OVERRIDE_TRACES_ENDPOINT before `wash up`
   - replacing existing wasmcloud host (in `~/.wash/downloads/v1.0.2`)
 - <csr-id-fa1fde185b47b055e511f6f2dee095e269db1651/> propagate traces through components
 - <csr-id-61308b7827789d442b2508ba5347add03bdbb069/> Fixes issue with running runtime on smaller hosts
   We found that on hosts with less then 2GB of memory (give or take a
   little) the host would fail to start when the pooling allocator started
   allocating virtual memory. You could get around this by setting
   `vm_overcommit` to 1 or 2, but this is not the best experience for those
   running in production. This fixes the issue by falling back to the
   dynamic memory allocator if setup fails.
   
   We already have a plan to add some more of these tunables as options
   for the host, but those will be added in future PRs as a feature add
 - <csr-id-7abc17038655db16e71471edd2cc7dc0a760b6ac/> rustdoc spelling
 - <csr-id-4ed38913f19fcd4dd44dfdcc9007e80e80cdc960/> fix `link_name` functionality, reorganize tests
 - <csr-id-ccb3c73dc1351b11233896abc068a200374df079/> correct name and data streaming, update WIT
 - <csr-id-bff9816db3193c57ccfe48852f21258a8430530e/> do not polyfill wasi:blobstore interfaces
 - <csr-id-c8f26b84346600870f62df05238f64421c6e66c6/> do not polyfill wasi cloud interfaces
 - <csr-id-149f98b60c1e70d0e68153add3e30b8fb4483e11/> improve target lookup error handling
 - <csr-id-0f6a1eb97cb46a43c9b24977a8e8dc11061af330/> add messaging triggered test actor
   This commit is the culmination of a few things that were required for
   getting our flavor of E2E tests (in the top level `tests/` dir)
   working for a Provider & Actor.
   
   This commit is quite large because it does many things:
   
   - Adds missing implementation to bindgen for provider -> actor invocations
   - Uncomments implementation from the host for wasmcloud:messaging
   - Adds an invoker component that reacts to messaging rather than HTTP
   - Uses messaging & keyvalue providers plus the actor in a single test
   
   With this, we have an easy to understand way to test every provider
   that we have in the repository.
 - <csr-id-d1c3a599377ccb46ba11f2d9484812dc2a67b22c/> do not polyfill logging
 - <csr-id-923c650cc4b58e5316e53ae8141219de15862d34/> tone down instrumentation level
 - <csr-id-e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12/> bindgen issues preventing builds
   This commit fixes the provider bindgen issues for non http-server
   builds (ex. kv-redis)
 - <csr-id-542427e4a0bff82c25ffe35c9587f34783a207dd/> parse package
 - <csr-id-c6fa704f001a394c10f8769d670941aff62d6414/> fix clippy warning, added ; for consistency, return directly the instance instead of wrapping the instance's components in a future
 - <csr-id-7db1183dbe84aeeb1967eb28d71876f6f175c2c2/> Add comments, remove useless future::ready
 - <csr-id-1d3fd96f2fe23c71b2ef70bb5199db8009c56154/> fmt
 - <csr-id-c555bab75cdc6f2953ec394b4fe41133d83efb66/> return `Ready` on trailers
 - <csr-id-1829b27213e836cb347a542e9cdc771c74427892/> allow namespaces with slashes
 - <csr-id-b13a50ca8b882fe5142f9ad26501ffeba47af24c/> properly handle `path_with_query`
 - <csr-id-a82847f4e4a2637bc9d6f9c75be0a902f7944212/> switch to wasmCloud messaging WIT

### Other

 - <csr-id-ef45f597710929d41be989110fc3c51621c9ee62/> bump wascap v0.15.2, provider-archive v0.14.0, wasmcloud-core v0.15.0, wash-lib v0.31.0, wasmcloud-tracing v0.11.0, wasmcloud-provider-sdk v0.12.0, wasmcloud-secrets-types v0.5.0, wash-cli v0.37.0, safety bump 9 crates
   SAFETY BUMP: wasmcloud-core v0.15.0, wash-lib v0.31.0, wasmcloud-tracing v0.11.0, wasmcloud-provider-sdk v0.12.0, wash-cli v0.37.0, wasmcloud-host v0.23.0, wasmcloud-runtime v0.7.0, wasmcloud-test-util v0.15.0, wasmcloud-secrets-client v0.6.0
 - <csr-id-f7b3232b5d5a5fae17f71aeec8c837e879021e34/> wasmcloud-runtime v0.4.0
 - <csr-id-b96a9bf8544c7ae6459971acff75865e8ab886bd/> wasmcloud-runtime v0.3.0
 - <csr-id-1af6e05f1a47be4e62a4c21d1704aff2e09bef89/> bump wasmcloud-core v0.10.0, safety bump 5 crates
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-tracing v0.8.0, wasmcloud-provider-sdk v0.9.0, wash-cli v0.33.0, wash-lib v0.26.0
 - <csr-id-d8f73f56a3ebb67ddb34acb6598039c51c05e772/> wasmcloud-runtime v0.2.0
 - <csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/> wasmcloud-runtime v0.1.0
 - <csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/> bump for test-util release
   Bump wasmcloud-core v0.8.0, opentelemetry-nats v0.1.1, provider-archive v0.12.0, wasmcloud-runtime v0.3.0, wasmcloud-secrets-types v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, safety bump 8 crates
   
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, wasmcloud-provider-sdk v0.7.0, wash-cli v0.30.0, wash-lib v0.23.0
 - <csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/> improve documentation
 - <csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/> clarify the instance exclusions
 - <csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/> update to Wasmtime 18
 - <csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/> update to wasmtime 17
 - <csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/> update to wasmtime 16
   Note this uses a release branch as 16 is not out yet.
 - <csr-id-a278764abaac2b745b833aaea8e041e357b97a15/> pin blobstore to upstream rev
   Pin until https://github.com/WebAssembly/wasi-blob-store/pull/14 merged
 - <csr-id-d16324054a454347044f7cc052da1bbd4324a284/> bump crate versions
 - <csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/> bump to `0.79.0`
 - <csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/> update dependencies
 - <csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/> switch to upstream `wasi:blobstore`
 - <csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/> update WIT dependencies
 - <csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/> update to Wasmtime 12
 - <csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/> update WIT dependencies
   This fixes `poll-oneof` mismatch
 - <csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/> update dependencies

### Refactor

 - <csr-id-0b679acb9cf52e6cf4ee883843ae5b275e222e6f/> rearrange imports according to default rust fmt
 - <csr-id-53a7eb5bf13dd986fe9435a8444d1ec4f09cd329/> minor changes, remove print
 - <csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/> use upstream preview1 adapter crate
 - <csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/> extract and document `InvocationStream` type
 - <csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/> wascap::jwt::Actor -> wascap::jwt::Component
 - <csr-id-e1281733c73988686a499d43e808e4cd11fd5759/> link actors on creation
 - <csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/> improve WASI linking error
 - <csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/> remove instance pooling
 - <csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/> reduce verbosity on actor logs
 - <csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/> component instantiation error message
 - <csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/> split interface implementations into separate modules

### Test

 - <csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/> replicate component test in modules and compat

### Chore (BREAKING)

 - <csr-id-5f7e0132362f7eda0710a1a69d5944140fd74b07/> Updates dependencies
   This does an update of pretty much all of the dependencies possible
   in the main tree. Any code changes were refactors maintaining the same
   behaviors, but using any updated APIs.
   
   This is noted as breaking because the updates to the crates bubble up
   through the `core` crate, so it technically breaks that API since we
   reexport. If we think that isn't worth it, I can revert that bit.

### New Features (BREAKING)

 - <csr-id-5f05bcc468b3e67e67a22c666d93176b44164fbc/> add checked set_link_name
 - <csr-id-fc1bbf45e212b2d00b654a27a38a7322e8889be6/> increase wasm memory limit, 256MiB
 - <csr-id-2c0b5860390373720845cc2060705ad7d942a3c3/> implement streaming in wasi:blobstore
 - <csr-id-f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71/> allow tuning runtime parameters
 - <csr-id-acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5/> add secrets store/reveal imports
 - <csr-id-6b2e1b5915a0e894a567622ffc193230e5654c1f/> Removes old guest config and uses runtime config instead
   Most of the changes are related to wit updates, but this removes the
   guest config from `wasmcloud:bus` and pulls down `wasi:config` in its
   place
 - <csr-id-91874e9f4bf2b37b895a4654250203144e12815c/> convert to `wrpc:blobstore`
 - <csr-id-716d251478cf174085f6ff274854ddebd9e0d772/> use `wasmcloud:messaging` in providers
   Also implement statically invoking the `handler` on components in the
   host
 - <csr-id-5af1138da6afa3ca6424d4ff10aa49211952c898/> support interface link put, component spec
 - <csr-id-42d069eee87d1b5befff1a95b49973064f1a1d1b/> Updates topics to the new standard
   This is a wide ranging PR that changes all the topics as described
   in #1108. This also involved removing the start and stop actor
   operations. While I was in different parts of the code I did some small
   "campfire rule" cleanups mostly of clippy lints and removal of
   clippy pedant mode.

### Refactor (BREAKING)

 - <csr-id-c36dee94832d111c2a3ba5ff9f5e26baf2f3e4d9/> Removes dependencies from host on provider libraries
   Our current host had a circular dependency loop with itself because it
   depended on the http and messaging providers. In order to break this, I
   moved the common http and messaging types we use for builtins into
   `wasmcloud-core` behind feature flags that aren't on by default. As such,
   this is a breaking change as I moved stuff around, but mostly didn't
   change any code.
   
   Please note that I only bumped version numbers on things we had released
   already. Some of these crates had not yet been released and do not need
   another bump

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 204 commits contributed to the release over the course of 687 calendar days.
 - 200 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Bump versions ([`7df6305`](https://github.com/wasmCloud/wasmCloud/commit/7df6305aac78635e26e478992509bb07915868d9))
    - Address clippy feedback ([`915c124`](https://github.com/wasmCloud/wasmCloud/commit/915c124e2907cb5dcfc4c1a6fbbf328b0ae2ade3))
    - Allow configurable core instances per component ([`745cf81`](https://github.com/wasmCloud/wasmCloud/commit/745cf8152e0403d59d0897e4edf540c15ac2867c))
    - Add `wasmcloud:bus/error.error` ([`6061eab`](https://github.com/wasmCloud/wasmCloud/commit/6061eabcd60c56de88ed275aa1b988afec9a426a))
    - Update wrpc and wasmtime ([`2c167ec`](https://github.com/wasmCloud/wasmCloud/commit/2c167ec361f35ac469a087d32a671813a11e0b71))
    - Removes dependencies from host on provider libraries ([`c36dee9`](https://github.com/wasmCloud/wasmCloud/commit/c36dee94832d111c2a3ba5ff9f5e26baf2f3e4d9))
    - Rename wasmcloud:identity@0.1.0-draft to wasmcloud:identity@0.0.1 ([`13d312c`](https://github.com/wasmCloud/wasmCloud/commit/13d312c5dc7dbd450a64fe98f3df01db3d5df6d0))
    - Add wasmcloud:identity interface for fetching component workload identity ([`e9e32ce`](https://github.com/wasmCloud/wasmCloud/commit/e9e32ced1cdc7d00e13bd268ddb78388fb03d1a0))
    - Bump provider-archive v0.16.0, wasmcloud-core v0.17.0, wasmcloud-tracing v0.13.0, wasmcloud-provider-sdk v0.14.0, wasmcloud-provider-http-server v0.27.0, wasmcloud-provider-messaging-nats v0.26.0, wasmcloud-runtime v0.9.0, wasmcloud-secrets-types v0.6.0, wasmcloud-secrets-client v0.7.0, wasmcloud-host v0.25.0, wasmcloud-test-util v0.17.0, secrets-nats-kv v0.2.0, wash v0.41.0 ([`3078c88`](https://github.com/wasmCloud/wasmCloud/commit/3078c88f0ebed96027e20997bccc1c125583fad4))
    - Updates dependencies ([`5f7e013`](https://github.com/wasmCloud/wasmCloud/commit/5f7e0132362f7eda0710a1a69d5944140fd74b07))
    - Update redis:keyvalue:watch configuration to be configurable by link config ([`3147765`](https://github.com/wasmCloud/wasmCloud/commit/3147765c1955119d54df26600738b8963abc792d))
    - Add wasi:keyvalue/watch handler and redis provider ([`ca530c7`](https://github.com/wasmCloud/wasmCloud/commit/ca530c77e94d755f3e4dff9e7d486dd6b1f7c2e7))
    - Bump for 0.8.1 release ([`3b45c85`](https://github.com/wasmCloud/wasmCloud/commit/3b45c855936a73ae588c77b0932647f25946cff5))
    - Extract suffix from version not name ([`aff0539`](https://github.com/wasmCloud/wasmCloud/commit/aff0539e8e707f88906630b6c33252671be8c97d))
    - Fully support WASI >0.2.2 ([`c20d617`](https://github.com/wasmCloud/wasmCloud/commit/c20d617710a8e9d82a1b5549d7dfaf7b1288f85a))
    - Address clippy warnings ([`98bf9ae`](https://github.com/wasmCloud/wasmCloud/commit/98bf9ae36fc321fc7803a7485f32b833907f036e))
    - Bump wasmcloud-core v0.16.0, wash-lib v0.32.0, wash-cli v0.38.0, safety bump 6 crates ([`4f30198`](https://github.com/wasmCloud/wasmCloud/commit/4f30198215220b3f9ce0c2aa6da8aa7d31a6a72d))
    - Gate messaging@v3 behind feature flag ([`febf47d`](https://github.com/wasmCloud/wasmCloud/commit/febf47d0ed7d70a245006710960a1a3bd695e6bf))
    - Address clippy warnings ([`e71198a`](https://github.com/wasmCloud/wasmCloud/commit/e71198a83c32dcce51f2e7e7a3a8fb953899c82a))
    - Attach OTEL context ([`e286c28`](https://github.com/wasmCloud/wasmCloud/commit/e286c285df542d818489c934d03ceedcf5f4135a))
    - Implement `wasmcloud:messaging@0.3.0` ([`8afa8ff`](https://github.com/wasmCloud/wasmCloud/commit/8afa8ff95db21c93d3b280edc39d477dc8a2aaac))
    - Rearrange imports according to default rust fmt ([`0b679ac`](https://github.com/wasmCloud/wasmCloud/commit/0b679acb9cf52e6cf4ee883843ae5b275e222e6f))
    - Add `wasmcloud:messaging@0.3.0` dependency ([`b7bdfed`](https://github.com/wasmCloud/wasmCloud/commit/b7bdfed2f043c6fbcf17ef6588c6b099057014a2))
    - Enable memory_init_cow in wasmtime ([`9adf2b5`](https://github.com/wasmCloud/wasmCloud/commit/9adf2b51b2e2c416c1b62040fc34e4e8a319b7a2))
    - Propagate outgoing context via store not handler ([`d1feac0`](https://github.com/wasmCloud/wasmCloud/commit/d1feac0b8abb8cb8e2eec665b4d9b38ec8cd6d7f))
    - Connect function trace to context ([`7413aeb`](https://github.com/wasmCloud/wasmCloud/commit/7413aeb39e7f3b2e7550cdefafe982d6ffbe2da6))
    - Propagate serve trace into handlers ([`c5c6be9`](https://github.com/wasmCloud/wasmCloud/commit/c5c6be96a3fe6dd3b7264ed7acf6b105404652be))
    - Add builtin `wasmcloud:messaging`, HTTP server ([`45fa6b0`](https://github.com/wasmCloud/wasmCloud/commit/45fa6b06216da820045e4d39838a6ac3bdf97075))
    - Removed unused dependencies ([`eb52eca`](https://github.com/wasmCloud/wasmCloud/commit/eb52eca817fe24b33e7f1a65c1ba5c46c50bef4e))
    - Bump wascap v0.15.2, provider-archive v0.14.0, wasmcloud-core v0.15.0, wash-lib v0.31.0, wasmcloud-tracing v0.11.0, wasmcloud-provider-sdk v0.12.0, wasmcloud-secrets-types v0.5.0, wash-cli v0.37.0, safety bump 9 crates ([`ef45f59`](https://github.com/wasmCloud/wasmCloud/commit/ef45f597710929d41be989110fc3c51621c9ee62))
    - Convert wasi-logging levels into more conventional format ([`68ea303`](https://github.com/wasmCloud/wasmCloud/commit/68ea303e2cb3a3bbfd6878bcc1884f4951ed693d))
    - End epoch interruption, don't await ([`44e1d0e`](https://github.com/wasmCloud/wasmCloud/commit/44e1d0ef5acd63fbb08f5887557d39ce74680378))
    - Bump wascap v0.15.1, wasmcloud-core v0.13.0, wash-lib v0.29.0, wasmcloud-tracing v0.10.0, wasmcloud-provider-sdk v0.11.0, wash-cli v0.36.0, safety bump 7 crates ([`c5ba85c`](https://github.com/wasmCloud/wasmCloud/commit/c5ba85cfe6ad63227445b0a5e21d58a8f3e15e33))
    - Add lattice@1.0.0 and @2.0.0 implementations ([`a7015f8`](https://github.com/wasmCloud/wasmCloud/commit/a7015f83af4d8d46284d3f49398ffa22876f290d))
    - Minor changes, remove print ([`53a7eb5`](https://github.com/wasmCloud/wasmCloud/commit/53a7eb5bf13dd986fe9435a8444d1ec4f09cd329))
    - Add checked set_link_name ([`5f05bcc`](https://github.com/wasmCloud/wasmCloud/commit/5f05bcc468b3e67e67a22c666d93176b44164fbc))
    - Add support for WASI 0.2.2 ([`b8c2b99`](https://github.com/wasmCloud/wasmCloud/commit/b8c2b999c979cd82f6772f3f98ec1d16c7f5565d))
    - Adds support for versioned wasi logging interface ([`5095c22`](https://github.com/wasmCloud/wasmCloud/commit/5095c22d266331cecdeacc0d29b0a4d08f5ab258))
    - Bump wasmcloud-core v0.12.0, wash-lib v0.28.0, wasmcloud-tracing v0.9.0, wasmcloud-provider-sdk v0.10.0, wash-cli v0.35.0, safety bump 7 crates ([`44bf4c8`](https://github.com/wasmCloud/wasmCloud/commit/44bf4c8793b3989aebbbc28c2f2ce3ebbd4d6a0a))
    - Wasmcloud-runtime v0.4.0 ([`f7b3232`](https://github.com/wasmCloud/wasmCloud/commit/f7b3232b5d5a5fae17f71aeec8c837e879021e34))
    - Wasmcloud-runtime v0.3.0 ([`b96a9bf`](https://github.com/wasmCloud/wasmCloud/commit/b96a9bf8544c7ae6459971acff75865e8ab886bd))
    - Update to WASI 0.2.1 ([`f509322`](https://github.com/wasmCloud/wasmCloud/commit/f5093226a252c35be1ea1e9ed9740923f33ec015))
    - Rework `wasi:http` error handling ([`4da0105`](https://github.com/wasmCloud/wasmCloud/commit/4da0105ac7bf463eeb79bc3047cb5e92664f8a7c))
    - Update to wasmtime 25 ([`c37c92a`](https://github.com/wasmCloud/wasmCloud/commit/c37c92abf8c93a40f8174c588e83b5242dcbc4c5))
    - Ensures we have the proper limits set for max components ([`853105c`](https://github.com/wasmCloud/wasmCloud/commit/853105c8ad06b92686589b669765bbdbd439ccbc))
    - Log handling errors ([`726dd68`](https://github.com/wasmCloud/wasmCloud/commit/726dd689e6d64eb44930834425d69f21cefc61cd))
    - Bump wasmcloud-core v0.10.0, safety bump 5 crates ([`1af6e05`](https://github.com/wasmCloud/wasmCloud/commit/1af6e05f1a47be4e62a4c21d1704aff2e09bef89))
    - Additional static instances ([`8f0e15e`](https://github.com/wasmCloud/wasmCloud/commit/8f0e15e01732e873e5861b1336254e21eafa0f10))
    - Adds support for batch support to the host ([`8575f73`](https://github.com/wasmCloud/wasmCloud/commit/8575f732df33ca973ff340fc3e4bc7fbfeaf89f3))
    - Wasmcloud-runtime v0.2.0 ([`d8f73f5`](https://github.com/wasmCloud/wasmCloud/commit/d8f73f56a3ebb67ddb34acb6598039c51c05e772))
    - Wasmcloud-runtime v0.1.0 ([`94adef8`](https://github.com/wasmCloud/wasmCloud/commit/94adef8c3cbf722025d2c8ca990b264b24030b72))
    - Increase wasm memory limit, 256MiB ([`fc1bbf4`](https://github.com/wasmCloud/wasmCloud/commit/fc1bbf45e212b2d00b654a27a38a7322e8889be6))
    - Enable wasmtime gc feature ([`056b57e`](https://github.com/wasmCloud/wasmCloud/commit/056b57e50cfc13ecd863f54d30032988bd23d94b))
    - Fallback to `wrpc:blobstore@0.1.0` ([`26d7f64`](https://github.com/wasmCloud/wasmCloud/commit/26d7f64659dbf3263f36da92df89003c579077cc))
    - Allow complex types ([`72cb5e7`](https://github.com/wasmCloud/wasmCloud/commit/72cb5e7db4d3323f7b09beb7f4fc7754379929d0))
    - Implement streaming in wasi:blobstore ([`2c0b586`](https://github.com/wasmCloud/wasmCloud/commit/2c0b5860390373720845cc2060705ad7d942a3c3))
    - Use upstream preview1 adapter crate ([`3fb79da`](https://github.com/wasmCloud/wasmCloud/commit/3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c))
    - Update to Wasmtime 23 ([`156d3f3`](https://github.com/wasmCloud/wasmCloud/commit/156d3f39e6775ec6aea3a1eb864bf7c893749e07))
    - Allow tuning runtime parameters ([`f4b4eeb`](https://github.com/wasmCloud/wasmCloud/commit/f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71))
    - Update component/runtime/host crate READMEs ([`51c8ceb`](https://github.com/wasmCloud/wasmCloud/commit/51c8ceb895b0069af9671e895b9f1ecb841ea6c3))
    - Bump for test-util release ([`7cd2e71`](https://github.com/wasmCloud/wasmCloud/commit/7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4))
    - Increase max memory size to 10mb ([`3c414c5`](https://github.com/wasmCloud/wasmCloud/commit/3c414c52d4dfd31094b4cd2cee7e2f159cad639f))
    - Add secrets store/reveal imports ([`acb6e9c`](https://github.com/wasmCloud/wasmCloud/commit/acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5))
    - Update wRPC ([`8fa3faa`](https://github.com/wasmCloud/wasmCloud/commit/8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58))
    - Improve documentation ([`78b9bc7`](https://github.com/wasmCloud/wasmCloud/commit/78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1))
    - Extract and document `InvocationStream` type ([`9463be2`](https://github.com/wasmCloud/wasmCloud/commit/9463be2cc3dcaf2e272e5372800e65378c16217f))
    - Remove unused logging exports ([`40874d4`](https://github.com/wasmCloud/wasmCloud/commit/40874d427a24c65746e18de44aef87cc4c3c4c13))
    - Address clippy warnings ([`bd50166`](https://github.com/wasmCloud/wasmCloud/commit/bd50166619b8810ccdc2bcd80c33ff80d94bc909))
    - Update to stream-based serving ([`0f70936`](https://github.com/wasmCloud/wasmCloud/commit/0f7093660a1ef09ff745daf5e1a96fd72c88984d))
    - Pass original component instance through the context ([`0707512`](https://github.com/wasmCloud/wasmCloud/commit/070751231e5bb4891b995e992e5206b3050ecc30))
    - Upgrade `wrpc`, `async-nats`, `wasmtime` ([`9cb1b78`](https://github.com/wasmCloud/wasmCloud/commit/9cb1b784fe7a8892d73bdb40d1172b1879fcd932))
    - Replace actor reference by component in runtime crate ([`4bf428d`](https://github.com/wasmCloud/wasmCloud/commit/4bf428dbf693f1c91c276513e75b492e57d4d1a6))
    - Improve error messages for missing links ([`e7c3040`](https://github.com/wasmCloud/wasmCloud/commit/e7c30405302fcccc612209335179f0bc47d8e996))
    - Add `TargetEntity::lattice_id()` ([`a5f9432`](https://github.com/wasmCloud/wasmCloud/commit/a5f9432845bcb7c8f423776fd56ef4a735fe43c7))
    - Setup debug traces ([`b014263`](https://github.com/wasmCloud/wasmCloud/commit/b014263cf3614995f597336bb40e51ab72bfa1c9))
    - Propagate traces through components ([`fa1fde1`](https://github.com/wasmCloud/wasmCloud/commit/fa1fde185b47b055e511f6f2dee095e269db1651))
    - Replace actor references by component in crates ([`20c72ce`](https://github.com/wasmCloud/wasmCloud/commit/20c72ce0ed423561ae6dbd5a91959bec24ff7cf3))
    - Fixes issue with running runtime on smaller hosts ([`61308b7`](https://github.com/wasmCloud/wasmCloud/commit/61308b7827789d442b2508ba5347add03bdbb069))
    - Gracefully shutdown epoch interrupt thread ([`077a28a`](https://github.com/wasmCloud/wasmCloud/commit/077a28a6567a436c99368c7eb1bd5dd2a6bc6103))
    - Generate changelogs after 1.0.1 release ([`4e0313a`](https://github.com/wasmCloud/wasmCloud/commit/4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e))
    - Updated with newest features ([`0f03f1f`](https://github.com/wasmCloud/wasmCloud/commit/0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6))
    - Generate crate changelogs ([`f986e39`](https://github.com/wasmCloud/wasmCloud/commit/f986e39450676dc598b92f13cb6e52b9c3200c0b))
    - Count epoch in a separate OS thread ([`3eb4534`](https://github.com/wasmCloud/wasmCloud/commit/3eb453405aa144599f43bbaf56197566c9f0cf0a))
    - Propagate `max_execution_time` to the runtime ([`a66921e`](https://github.com/wasmCloud/wasmCloud/commit/a66921edd9be3202d1296a165c34faf597b1dec1))
    - Limit max execution time to 10 minutes ([`e928020`](https://github.com/wasmCloud/wasmCloud/commit/e928020fd774abcc213fec560d89f128464da319))
    - Replace references to 'actor' with 'component' ([`7702e69`](https://github.com/wasmCloud/wasmCloud/commit/7702e695cd9ab9436aaeb337373c3c1cb31f324a))
    - Update to Wasmtime 20 ([`33b50c2`](https://github.com/wasmCloud/wasmCloud/commit/33b50c2d258ca9744ed65b153a6580f893172e0c))
    - Update `wrpc:keyvalue` in providers ([`9cd2b40`](https://github.com/wasmCloud/wasmCloud/commit/9cd2b4034f8d5688ce250429dc14120eaf61b483))
    - Update `wasi:keyvalue` ([`a175419`](https://github.com/wasmCloud/wasmCloud/commit/a1754195fca5a13c8cdde713dad3e1a9765adaf5))
    - Clarify the instance exclusions ([`663b49e`](https://github.com/wasmCloud/wasmCloud/commit/663b49e335d2645d0cfd679afd202ca461dd6932))
    - Update `messaging` to `0.2.0` ([`955a689`](https://github.com/wasmCloud/wasmCloud/commit/955a6893792e86292883e76de57434616c28d380))
    - Bumps our wasmcloud wit to 1.0 ([`2352092`](https://github.com/wasmCloud/wasmCloud/commit/2352092930b50992e47e7fcf013ae5f084bf2a8e))
    - Removes old guest config and uses runtime config instead ([`6b2e1b5`](https://github.com/wasmCloud/wasmCloud/commit/6b2e1b5915a0e894a567622ffc193230e5654c1f))
    - Rustdoc spelling ([`7abc170`](https://github.com/wasmCloud/wasmCloud/commit/7abc17038655db16e71471edd2cc7dc0a760b6ac))
    - Wascap::jwt::Actor -> wascap::jwt::Component ([`468268e`](https://github.com/wasmCloud/wasmCloud/commit/468268e015ccc5d5d8a607dcf3ede7c5e86de45e))
    - Reenable `clippy::pedantic` ([`327975d`](https://github.com/wasmCloud/wasmCloud/commit/327975d6a83bac3199240645b0c6a4a17cf00f66))
    - Update to wasmtime 19 ([`023358b`](https://github.com/wasmCloud/wasmCloud/commit/023358b41b154e75a737f10f652e197dfa6b0093))
    - Migrate to `wrpc:keyvalue` ([`f56492a`](https://github.com/wasmCloud/wasmCloud/commit/f56492ac6b5e6f1274a1f11b061c42cace372122))
    - Fix `link_name` functionality, reorganize tests ([`4ed3891`](https://github.com/wasmCloud/wasmCloud/commit/4ed38913f19fcd4dd44dfdcc9007e80e80cdc960))
    - Convert to `wrpc:blobstore` ([`91874e9`](https://github.com/wasmCloud/wasmCloud/commit/91874e9f4bf2b37b895a4654250203144e12815c))
    - Remove unused dependencies ([`1bad246`](https://github.com/wasmCloud/wasmCloud/commit/1bad246d9e174384c1a09bdff7e2dc88d911792e))
    - Correct name and data streaming, update WIT ([`ccb3c73`](https://github.com/wasmCloud/wasmCloud/commit/ccb3c73dc1351b11233896abc068a200374df079))
    - Use `wasmcloud:messaging` in providers ([`716d251`](https://github.com/wasmCloud/wasmCloud/commit/716d251478cf174085f6ff274854ddebd9e0d772))
    - Implement `wrpc:blobstore/blobstore` for FS ([`383b3f3`](https://github.com/wasmCloud/wasmCloud/commit/383b3f3067dddc913d5a0c052f7bbb9c47fe8663))
    - Do not polyfill wasi:blobstore interfaces ([`bff9816`](https://github.com/wasmCloud/wasmCloud/commit/bff9816db3193c57ccfe48852f21258a8430530e))
    - Implement Redis `wrpc:keyvalue/{atomic,eventual}` ([`614af7e`](https://github.com/wasmCloud/wasmCloud/commit/614af7e3ed734c56b27cd1d2aacb0789a85e8b81))
    - Implement `wasi:http/outgoing-handler` provider ([`e0dac9d`](https://github.com/wasmCloud/wasmCloud/commit/e0dac9de4d3a74424e3138971753db9da143db5a))
    - Remove compat crate ([`f2aed15`](https://github.com/wasmCloud/wasmCloud/commit/f2aed15288300989aca03f899b095d3a71f8e5cd))
    - Do not polyfill wasi cloud interfaces ([`c8f26b8`](https://github.com/wasmCloud/wasmCloud/commit/c8f26b84346600870f62df05238f64421c6e66c6))
    - Update WIT dependencies ([`5e45723`](https://github.com/wasmCloud/wasmCloud/commit/5e4572379d370de74dad4b393746fee242e374f2))
    - Support p1 module execution ([`0c5aee7`](https://github.com/wasmCloud/wasmCloud/commit/0c5aee7621f01f6a3a90322c55836f45184df79a))
    - Improve target lookup error handling ([`149f98b`](https://github.com/wasmCloud/wasmCloud/commit/149f98b60c1e70d0e68153add3e30b8fb4483e11))
    - Add messaging triggered test actor ([`0f6a1eb`](https://github.com/wasmCloud/wasmCloud/commit/0f6a1eb97cb46a43c9b24977a8e8dc11061af330))
    - Move CallTargetInterface to core ([`0d90023`](https://github.com/wasmCloud/wasmCloud/commit/0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb))
    - Support pubsub on wRPC subjects ([`76c1ed7`](https://github.com/wasmCloud/wasmCloud/commit/76c1ed7b5c49152aabd83d27f0b8955d7f874864))
    - Switches runtime config to use a pooling allocator ([`590a494`](https://github.com/wasmCloud/wasmCloud/commit/590a49477d5832ec99f3b2e251813d51b4abb274))
    - Improve byte stream efficiency ([`400802a`](https://github.com/wasmCloud/wasmCloud/commit/400802ac767a06459fc1d93c3ab5cd4223e8506f))
    - Do not polyfill logging ([`d1c3a59`](https://github.com/wasmCloud/wasmCloud/commit/d1c3a599377ccb46ba11f2d9484812dc2a67b22c))
    - Tone down instrumentation level ([`923c650`](https://github.com/wasmCloud/wasmCloud/commit/923c650cc4b58e5316e53ae8141219de15862d34))
    - Switches modules to use pre instantiation instead ([`25e3e51`](https://github.com/wasmCloud/wasmCloud/commit/25e3e51d7e123aae3e3681886d2e095b29202b94))
    - Simplify error handling ([`d61303d`](https://github.com/wasmCloud/wasmCloud/commit/d61303d1b08b568ae4925120b1f36ed690d4b038))
    - Implement `wrpc:http/incoming-handler` ([`f2223a3`](https://github.com/wasmCloud/wasmCloud/commit/f2223a3f5378c3cebfec96b5322df619fcecc556))
    - Switch to `wrpc` for `wasmcloud:messaging` ([`0c0c004`](https://github.com/wasmCloud/wasmCloud/commit/0c0c004bafb60323018fc1c86cb13493f72d29cd))
    - Switch to `wrpc:{keyvalue,blobstore}` ([`5ede01b`](https://github.com/wasmCloud/wasmCloud/commit/5ede01b1fe0bc62234d2b7d6c72775d9e248a130))
    - Implement `wrpc:http/outgoing-handler.handle` ([`2463845`](https://github.com/wasmCloud/wasmCloud/commit/246384524cfe65ce6742558425b885247b461c5c))
    - Fix clippy lints ([`b83082a`](https://github.com/wasmCloud/wasmCloud/commit/b83082ad1a065cd4c0ba08512471f9b3474df6dc))
    - Bindgen issues preventing builds ([`e9bea42`](https://github.com/wasmCloud/wasmCloud/commit/e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12))
    - Integrate set-link-name and wrpc ([`4f55396`](https://github.com/wasmCloud/wasmCloud/commit/4f55396a0340d65dbebdf6d4f0ca070d6f990fc4))
    - Change set-target to set-link-name ([`5d19ba1`](https://github.com/wasmCloud/wasmCloud/commit/5d19ba16a98dca9439628e8449309ccaa763ab10))
    - Record polyfilled component imports ([`5d1590e`](https://github.com/wasmCloud/wasmCloud/commit/5d1590e231f75e4d418a5115b3449dda0dadec9a))
    - Remove `Actor` abstraction ([`45445a6`](https://github.com/wasmCloud/wasmCloud/commit/45445a6accd4d4322d192d201f315aa2ca2cb92b))
    - Fix custom interface support and tests ([`18875a7`](https://github.com/wasmCloud/wasmCloud/commit/18875a7264ec4b8c0a82f3389be72267be202e58))
    - Remove module support ([`fec6f5f`](https://github.com/wasmCloud/wasmCloud/commit/fec6f5f1372a1de5737f5ec585ad735e14c20480))
    - Import `wrpc-runtime-wasmtime` ([`22e71e5`](https://github.com/wasmCloud/wasmCloud/commit/22e71e59be566136f6028393153827662ec9f68e))
    - Add resource handling stubs ([`2193423`](https://github.com/wasmCloud/wasmCloud/commit/219342386861f21fab64429cad4f8e88ae679c0a))
    - Parse package ([`542427e`](https://github.com/wasmCloud/wasmCloud/commit/542427e4a0bff82c25ffe35c9587f34783a207dd))
    - Support composite types ([`eb61ce2`](https://github.com/wasmCloud/wasmCloud/commit/eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a))
    - Remove `wit-component` dep ([`6678fea`](https://github.com/wasmCloud/wasmCloud/commit/6678fead03a5d4ea893b74863b0fe043ff81a3d1))
    - Appease Clippy ([`9dc14c5`](https://github.com/wasmCloud/wasmCloud/commit/9dc14c54eb133c08dace6e6a6f96f915f0fcda6f))
    - Support composite Wasmtime type reflection in polyfills ([`da6e2b3`](https://github.com/wasmCloud/wasmCloud/commit/da6e2b3a91013c8564c22f8305d665aec78a072d))
    - Update to Wasmtime 18 ([`03c9d1c`](https://github.com/wasmCloud/wasmCloud/commit/03c9d1c6ae662d3018ebc9d4d8c509076e291f12))
    - Support interface link put, component spec ([`5af1138`](https://github.com/wasmCloud/wasmCloud/commit/5af1138da6afa3ca6424d4ff10aa49211952c898))
    - Add (most of) custom interface plumbing ([`713e774`](https://github.com/wasmCloud/wasmCloud/commit/713e7746a9aa61ceff373cf62cf85e68617fa788))
    - Updates topics to the new standard ([`42d069e`](https://github.com/wasmCloud/wasmCloud/commit/42d069eee87d1b5befff1a95b49973064f1a1d1b))
    - Fix clippy warning, added ; for consistency, return directly the instance instead of wrapping the instance's components in a future ([`c6fa704`](https://github.com/wasmCloud/wasmCloud/commit/c6fa704f001a394c10f8769d670941aff62d6414))
    - Add comments, remove useless future::ready ([`7db1183`](https://github.com/wasmCloud/wasmCloud/commit/7db1183dbe84aeeb1967eb28d71876f6f175c2c2))
    - Fmt ([`1d3fd96`](https://github.com/wasmCloud/wasmCloud/commit/1d3fd96f2fe23c71b2ef70bb5199db8009c56154))
    - Fix(1365): Encapsulate in spawn instance's process in response to a nats event. Also encapsulate the .clone on the wasmtime module. After this two modification the workload spread on all core of the CPU. Relates to issue https://github.com/wasmCloud/wasmCloud/issues/1365 ([`ba7590a`](https://github.com/wasmCloud/wasmCloud/commit/ba7590ab56083173f2abbe214add648e32c2591d))
    - Switch wasi-keyvalue to `main` ([`eee6c73`](https://github.com/wasmCloud/wasmCloud/commit/eee6c73122b715d6991bb6c76f04d29fc9319fe0))
    - Fix `wasi-keyvalue` incoming value ownership mismatch ([`089b895`](https://github.com/wasmCloud/wasmCloud/commit/089b8955d309b1cab3eaa45f03d394656deada55))
    - Implement preview 2 interfaces ([`08b8a3c`](https://github.com/wasmCloud/wasmCloud/commit/08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75))
    - Update WIT packages ([`a7e0e13`](https://github.com/wasmCloud/wasmCloud/commit/a7e0e130343f5a3ca4874035016c9b5a181a917a))
    - Update to wasmtime 17 ([`49f3883`](https://github.com/wasmCloud/wasmCloud/commit/49f3883c586c098d4b0be44793057b97566ec2e1))
    - Update to wasmtime 16 ([`75c0739`](https://github.com/wasmCloud/wasmCloud/commit/75c0739a4db4264996a7fa87ce3ae39f56780759))
    - Remove logging `with` pin ([`8b7152a`](https://github.com/wasmCloud/wasmCloud/commit/8b7152a5a702d56f70930302b5fe6e7b76858979))
    - Pin blobstore to upstream rev ([`a278764`](https://github.com/wasmCloud/wasmCloud/commit/a278764abaac2b745b833aaea8e041e357b97a15))
    - Update to Wasmtime 15 ([`7a6e6a0`](https://github.com/wasmCloud/wasmCloud/commit/7a6e6a0dc69720ed4b52a476539970811f5bac72))
    - Adds some additional context around test failures I was seeing ([`64d21b1`](https://github.com/wasmCloud/wasmCloud/commit/64d21b1f3d413e4c5da78d8045c1366c3782a190))
    - Adds support for actor config ([`1a048a7`](https://github.com/wasmCloud/wasmCloud/commit/1a048a71320dbbf58f331e7e958f4b1cd5ed4537))
    - Polish tracing and logging levels ([`2389f27`](https://github.com/wasmCloud/wasmCloud/commit/2389f27f0b570164a895a37abd462be2d68f20be))
    - Link actors on creation ([`e128173`](https://github.com/wasmCloud/wasmCloud/commit/e1281733c73988686a499d43e808e4cd11fd5759))
    - Implement wasifills for simple types ([`cfb66f8`](https://github.com/wasmCloud/wasmCloud/commit/cfb66f81180a3b47d6e7df1a444a1ec945115b15))
    - Improve WASI linking error ([`770731c`](https://github.com/wasmCloud/wasmCloud/commit/770731ca949c5906ccbd102bcf13dc57a870f7b7))
    - Merge pull request #807 from rvolosatovs/merge/wash ([`f2bc010`](https://github.com/wasmCloud/wasmCloud/commit/f2bc010110d96fc21bc3502798543b7d5b68b1b5))
    - Integrate `wash` into the workspace ([`dfad0be`](https://github.com/wasmCloud/wasmCloud/commit/dfad0be609868cbd0f0ce97d7d9238b41996b5fc))
    - Implement outgoing HTTP ([`2e8982c`](https://github.com/wasmCloud/wasmCloud/commit/2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3))
    - Return `Ready` on trailers ([`c555bab`](https://github.com/wasmCloud/wasmCloud/commit/c555bab75cdc6f2953ec394b4fe41133d83efb66))
    - Bump crate versions ([`d163240`](https://github.com/wasmCloud/wasmCloud/commit/d16324054a454347044f7cc052da1bbd4324a284))
    - Update to Wasmtime 14 and latest WIT ([`831e901`](https://github.com/wasmCloud/wasmCloud/commit/831e90192f258dff1060c7ac8bd9425009ab8335))
    - Resolve 1.73.0 warnings ([`93c0981`](https://github.com/wasmCloud/wasmCloud/commit/93c0981a4d69bc8f8fe06e6139e78e7f700a3115))
    - Reduce verbosity of instrumented functions ([`0023f7e`](https://github.com/wasmCloud/wasmCloud/commit/0023f7e86d5a40a534f623b7220743f27871549e))
    - Bump to `0.79.0` ([`578c72d`](https://github.com/wasmCloud/wasmCloud/commit/578c72d3333f1b9c343437946114c3cd6a0eead4))
    - Mark non-exhaustive Debug impls as such ([`099ebcd`](https://github.com/wasmCloud/wasmCloud/commit/099ebcd9855b13b810f8fbb11ac57816e9dd4c06))
    - Update dependencies ([`22276ff`](https://github.com/wasmCloud/wasmCloud/commit/22276ff61bcb4992b557f7af6624c9715f72c32b))
    - Remove instance pooling ([`017e6d4`](https://github.com/wasmCloud/wasmCloud/commit/017e6d40841f14b2158cf2ff70ca2ac8940e4b84))
    - Allow namespaces with slashes ([`1829b27`](https://github.com/wasmCloud/wasmCloud/commit/1829b27213e836cb347a542e9cdc771c74427892))
    - Include context on host errors ([`0e6e2da`](https://github.com/wasmCloud/wasmCloud/commit/0e6e2da7720e469b85940cadde3756b2afd64f7c))
    - Reduce verbosity on actor logs ([`6c42d5c`](https://github.com/wasmCloud/wasmCloud/commit/6c42d5c50375cdc2d12c86513a98b45135f0d187))
    - Properly handle `path_with_query` ([`b13a50c`](https://github.com/wasmCloud/wasmCloud/commit/b13a50ca8b882fe5142f9ad26501ffeba47af24c))
    - Add support for call aliases ([`123cb2f`](https://github.com/wasmCloud/wasmCloud/commit/123cb2f9b8981c37bc333fece71c009ce875e30f))
    - Remove noisy fields from instruments ([`4fb8206`](https://github.com/wasmCloud/wasmCloud/commit/4fb8206e1d5fb21892a01b9e4f009e48c8bea2df))
    - Support chunking and dechunking of requests ([`813ce52`](https://github.com/wasmCloud/wasmCloud/commit/813ce52a9c11270814eec051dfaa8817bf9f567d))
    - Switch to upstream `wasi:blobstore` ([`3179982`](https://github.com/wasmCloud/wasmCloud/commit/31799820202aa3556f6ad84ca5550402e6da0fef))
    - Implement `wasi:blobstore` ([`bef159a`](https://github.com/wasmCloud/wasmCloud/commit/bef159ab4d5ce6ba73e7c3465110c2990da64eac))
    - Switch to wasmCloud messaging WIT ([`a82847f`](https://github.com/wasmCloud/wasmCloud/commit/a82847f4e4a2637bc9d6f9c75be0a902f7944212))
    - Update WIT dependencies ([`083f8e8`](https://github.com/wasmCloud/wasmCloud/commit/083f8e833889a49d09a4dafa1998a58f7380562a))
    - Partially implement `wasi:keyvalue/atomic` ([`d434e14`](https://github.com/wasmCloud/wasmCloud/commit/d434e148620d394856246ac34bb0a64c37181970))
    - Component instantiation error message ([`b5aac8e`](https://github.com/wasmCloud/wasmCloud/commit/b5aac8ea84af9cc37282b99826b2da0c0ec297bc))
    - Update to Wasmtime 12 ([`1f3448e`](https://github.com/wasmCloud/wasmCloud/commit/1f3448e6b38ffdad064d79145470ca1a7a476508))
    - Implement `wasmcloud:http/incoming-handler` support ([`50d0ed1`](https://github.com/wasmCloud/wasmCloud/commit/50d0ed1086c5f417ed64dcce139cc3c2b50ca14c))
    - Replicate component test in modules and compat ([`5f92225`](https://github.com/wasmCloud/wasmCloud/commit/5f922256e679091e6acbb3e0f39852abb840c8b0))
    - Move builtin smithy structs to `compat` ([`54f0afa`](https://github.com/wasmCloud/wasmCloud/commit/54f0afa7b7d67b658113eb2a7ea667b77ea4bd55))
    - Implement link names and a2a calls ([`2e3bd2b`](https://github.com/wasmCloud/wasmCloud/commit/2e3bd2bd7611e5de9fe123f53778f282613eb0de))
    - Implement `wasmcloud:messaging/consumer` support ([`77d663d`](https://github.com/wasmCloud/wasmCloud/commit/77d663d3e1fd5590177ac8003a313a3edf29ab1f))
    - Implement `wasi:keyvalue/readwrite` support ([`02c1ddc`](https://github.com/wasmCloud/wasmCloud/commit/02c1ddc0d62b40f63afe4d270643ebc3bf39c081))
    - Split interface implementations into separate modules ([`2540b2a`](https://github.com/wasmCloud/wasmCloud/commit/2540b2a2776c8977e47232993b2af5086dc92e18))
    - Introduce Blobstore trait ([`9eda090`](https://github.com/wasmCloud/wasmCloud/commit/9eda090fe6d790f239093738515570a7886eae8d))
    - Update WIT dependencies ([`2bb60f3`](https://github.com/wasmCloud/wasmCloud/commit/2bb60f364ef573e5837c5299eb587ec4e1427d3f))
    - Implement actor -> provider linking ([`4de853a`](https://github.com/wasmCloud/wasmCloud/commit/4de853a1d3e28126faf9efa51aaa97714af7b493))
    - Provide wasmCloud interface stubs ([`3ae7cce`](https://github.com/wasmCloud/wasmCloud/commit/3ae7cce621b4be163feac7be903f3ff66f40ddc3))
    - Update dependencies ([`cb86378`](https://github.com/wasmCloud/wasmCloud/commit/cb86378831e48368d31947b0a44ef39080fe6d70))
    - Merge pull request #396 from rvolosatovs/feat/provider-sdk ([`6ed04f0`](https://github.com/wasmCloud/wasmCloud/commit/6ed04f00a335333196f6bafb96f2c40155537df3))
    - Implement linkdef add/delete ([`e943eca`](https://github.com/wasmCloud/wasmCloud/commit/e943eca7512a0d96a617451e2e2af78718d0f685))
    - Implement data streaming ([`7364dd8`](https://github.com/wasmCloud/wasmCloud/commit/7364dd8afae5c8884ca923b39c5680c60d8d0e3d))
</details>

## 0.4.0 (2024-09-28)

<csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/>
<csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/>
<csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/>
<csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/>
<csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/>
<csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/>
<csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/>
<csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/>
<csr-id-e7c30405302fcccc612209335179f0bc47d8e996/>
<csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/>
<csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/>
<csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/>
<csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/>
<csr-id-955a6893792e86292883e76de57434616c28d380/>
<csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/>
<csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/>
<csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/>
<csr-id-5e4572379d370de74dad4b393746fee242e374f2/>
<csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/>
<csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/>
<csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/>
<csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/>
<csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/>
<csr-id-22e71e59be566136f6028393153827662ec9f68e/>
<csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/>
<csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/>
<csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/>
<csr-id-089b8955d309b1cab3eaa45f03d394656deada55/>
<csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/>
<csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/>
<csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/>
<csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/>
<csr-id-2389f27f0b570164a895a37abd462be2d68f20be/>
<csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/>
<csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/>
<csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/>
<csr-id-0023f7e86d5a40a534f623b7220743f27871549e/>
<csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/>
<csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/>
<csr-id-b96a9bf8544c7ae6459971acff75865e8ab886bd/>
<csr-id-1af6e05f1a47be4e62a4c21d1704aff2e09bef89/>
<csr-id-d8f73f56a3ebb67ddb34acb6598039c51c05e772/>
<csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/>
<csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/>
<csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/>
<csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/>
<csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/>
<csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/>
<csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/>
<csr-id-a278764abaac2b745b833aaea8e041e357b97a15/>
<csr-id-d16324054a454347044f7cc052da1bbd4324a284/>
<csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/>
<csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/>
<csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/>
<csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/>
<csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/>
<csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/>
<csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/>
<csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/>
<csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/>
<csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/>
<csr-id-e1281733c73988686a499d43e808e4cd11fd5759/>
<csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/>
<csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/>
<csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/>
<csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/>
<csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/>
<csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/>

### Chore

 - <csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/> allow complex types
 - <csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/> update component/runtime/host crate READMEs
 - <csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/> increase max memory size to 10mb
   This commit increases the max memory that can be addressed by a single
   component to 10mb.
 - <csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/> update wRPC
 - <csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/> remove unused logging exports
 - <csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/> address clippy warnings
 - <csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/> update to stream-based serving
 - <csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/> Replace actor reference by component in runtime crate
 - <csr-id-e7c30405302fcccc612209335179f0bc47d8e996/> improve error messages for missing links
   When known interfaces are accessed, we show a message that notes that
   the target is unknown, but we can improve on that by alerting the user
   to a possibly missing link.
 - <csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/> Replace actor references by component in crates
   Rename wash-cli wash-build tests name and references
   
   Fix nix flake path to Cargo.lock file
   
   Fix format
   
   Rename in wash-cli tests
 - <csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/> generate changelogs after 1.0.1 release
 - <csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/> updated with newest features
 - <csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/> replace references to 'actor' with 'component'
 - <csr-id-955a6893792e86292883e76de57434616c28d380/> update `messaging` to `0.2.0`
 - <csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/> reenable `clippy::pedantic`
 - <csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/> remove unused dependencies
 - <csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/> remove compat crate
 - <csr-id-5e4572379d370de74dad4b393746fee242e374f2/> update WIT dependencies
 - <csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/> move CallTargetInterface to core
 - <csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/> simplify error handling
 - <csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/> fix clippy lints
 - <csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/> integrate set-link-name and wrpc
 - <csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/> remove `Actor` abstraction
 - <csr-id-22e71e59be566136f6028393153827662ec9f68e/> import `wrpc-runtime-wasmtime`
 - <csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/> remove `wit-component` dep
   Ciao
 - <csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/> appease Clippy
   Chillax, Clip
 - <csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/> switch wasi-keyvalue to `main`
 - <csr-id-089b8955d309b1cab3eaa45f03d394656deada55/> fix `wasi-keyvalue` incoming value ownership mismatch
 - <csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/> implement preview 2 interfaces
 - <csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/> update WIT packages
 - <csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/> remove logging `with` pin
 - <csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/> update to Wasmtime 15
 - <csr-id-2389f27f0b570164a895a37abd462be2d68f20be/> polish tracing and logging levels
 - <csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/> integrate `wash` into the workspace
 - <csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/> update to Wasmtime 14 and latest WIT
 - <csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/> resolve 1.73.0 warnings
 - <csr-id-0023f7e86d5a40a534f623b7220743f27871549e/> reduce verbosity of instrumented functions
 - <csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/> mark non-exhaustive Debug impls as such
 - <csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/> remove noisy fields from instruments

### New Features

<csr-id-cfb66f81180a3b47d6e7df1a444a1ec945115b15/>
<csr-id-2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3/>
<csr-id-123cb2f9b8981c37bc333fece71c009ce875e30f/>
<csr-id-813ce52a9c11270814eec051dfaa8817bf9f567d/>
<csr-id-bef159ab4d5ce6ba73e7c3465110c2990da64eac/>
<csr-id-d434e148620d394856246ac34bb0a64c37181970/>
<csr-id-50d0ed1086c5f417ed64dcce139cc3c2b50ca14c/>
<csr-id-54f0afa7b7d67b658113eb2a7ea667b77ea4bd55/>
<csr-id-2e3bd2bd7611e5de9fe123f53778f282613eb0de/>
<csr-id-77d663d3e1fd5590177ac8003a313a3edf29ab1f/>
<csr-id-02c1ddc0d62b40f63afe4d270643ebc3bf39c081/>
<csr-id-9eda090fe6d790f239093738515570a7886eae8d/>
<csr-id-4de853a1d3e28126faf9efa51aaa97714af7b493/>
<csr-id-3ae7cce621b4be163feac7be903f3ff66f40ddc3/>
<csr-id-e943eca7512a0d96a617451e2e2af78718d0f685/>
<csr-id-7364dd8afae5c8884ca923b39c5680c60d8d0e3d/>

 - <csr-id-f5093226a252c35be1ea1e9ed9740923f33ec015/> update to WASI 0.2.1
 - <csr-id-c37c92abf8c93a40f8174c588e83b5242dcbc4c5/> update to wasmtime 25
 - <csr-id-8575f732df33ca973ff340fc3e4bc7fbfeaf89f3/> Adds support for batch support to the host
   This enables keyvalue batch support inside of the host, along with a test
   to make sure it works. Not all of our providers implement batch yet, so
   this uses the Redis provider, which did have implementions. I did have to
   fix the redis provider to get the right type of data back and transform
   it. I also had to update our wRPC versions so we could pick up on some
   bug fixes for the types we are encoding in the batch interface.
 - <csr-id-056b57e50cfc13ecd863f54d30032988bd23d94b/> enable wasmtime gc feature
 - <csr-id-26d7f64659dbf3263f36da92df89003c579077cc/> fallback to `wrpc:blobstore@0.1.0`
 - <csr-id-156d3f39e6775ec6aea3a1eb864bf7c893749e07/> update to Wasmtime 23
 - <csr-id-070751231e5bb4891b995e992e5206b3050ecc30/> pass original component instance through the context
 - <csr-id-9cb1b784fe7a8892d73bdb40d1172b1879fcd932/> upgrade `wrpc`, `async-nats`, `wasmtime`
 - <csr-id-a5f9432845bcb7c8f423776fd56ef4a735fe43c7/> add `TargetEntity::lattice_id()`
 - <csr-id-077a28a6567a436c99368c7eb1bd5dd2a6bc6103/> gracefully shutdown epoch interrupt thread
 - <csr-id-f986e39450676dc598b92f13cb6e52b9c3200c0b/> generate crate changelogs
 - <csr-id-3eb453405aa144599f43bbaf56197566c9f0cf0a/> count epoch in a separate OS thread
 - <csr-id-a66921edd9be3202d1296a165c34faf597b1dec1/> propagate `max_execution_time` to the runtime
 - <csr-id-e928020fd774abcc213fec560d89f128464da319/> limit max execution time to 10 minutes
 - <csr-id-33b50c2d258ca9744ed65b153a6580f893172e0c/> update to Wasmtime 20
 - <csr-id-9cd2b4034f8d5688ce250429dc14120eaf61b483/> update `wrpc:keyvalue` in providers
   part of this process is adopting `wit-bindgen-wrpc` in the host
 - <csr-id-a1754195fca5a13c8cdde713dad3e1a9765adaf5/> update `wasi:keyvalue`
 - <csr-id-2352092930b50992e47e7fcf013ae5f084bf2a8e/> Bumps our wasmcloud wit to 1.0
   This bumps our main `wasmcloud:bus` package and the package in the `runtime`
   crate to 1.0.0 in preparation for release. Also removes the use of
   the wasmcloud interface in tests where it wasn't needed
 - <csr-id-023358b41b154e75a737f10f652e197dfa6b0093/> update to wasmtime 19
 - <csr-id-f56492ac6b5e6f1274a1f11b061c42cace372122/> migrate to `wrpc:keyvalue`
 - <csr-id-383b3f3067dddc913d5a0c052f7bbb9c47fe8663/> implement `wrpc:blobstore/blobstore` for FS
 - <csr-id-614af7e3ed734c56b27cd1d2aacb0789a85e8b81/> implement Redis `wrpc:keyvalue/{atomic,eventual}`
 - <csr-id-e0dac9de4d3a74424e3138971753db9da143db5a/> implement `wasi:http/outgoing-handler` provider
 - <csr-id-0c5aee7621f01f6a3a90322c55836f45184df79a/> support p1 module execution
 - <csr-id-76c1ed7b5c49152aabd83d27f0b8955d7f874864/> support pubsub on wRPC subjects
   Up until now, publishing and subscribing for RPC communcations on the
   NATS cluster happened on subjects that were related to the wasmbus
   protocol (i.e. 'wasmbus.rpc.*').
   
   To support the WIT-native invocations, i.e. wRPC (#1389), we must
   change the publication and subscription subjects to include also the
   subjects that are expected to be used by wprc.
   
   This commit updates the provider-sdk to listen *additionally* to
   subjects that are required/used by wrpc, though we do not yet have an
   implementation for encode/deocde.
 - <csr-id-590a49477d5832ec99f3b2e251813d51b4abb274/> Switches runtime config to use a pooling allocator
   This leads to significant performance increases on Linux and brings it
   up to the same performance levels as other operating systems
 - <csr-id-400802ac767a06459fc1d93c3ab5cd4223e8506f/> improve byte stream efficiency
 - <csr-id-25e3e51d7e123aae3e3681886d2e095b29202b94/> Switches modules to use pre instantiation instead
   In my load testing of this locally, this led to a 20% increase in throughput
 - <csr-id-f2223a3f5378c3cebfec96b5322df619fcecc556/> implement `wrpc:http/incoming-handler`
 - <csr-id-0c0c004bafb60323018fc1c86cb13493f72d29cd/> switch to `wrpc` for `wasmcloud:messaging`
 - <csr-id-5ede01b1fe0bc62234d2b7d6c72775d9e248a130/> switch to `wrpc:{keyvalue,blobstore}`
 - <csr-id-246384524cfe65ce6742558425b885247b461c5c/> implement `wrpc:http/outgoing-handler.handle`
 - <csr-id-5d19ba16a98dca9439628e8449309ccaa763ab10/> change set-target to set-link-name
   Up until the relatively low-level `wasmcloud:bus/lattice` WIT
   interface has used a function called `set-target` to aim invocations
   that occurred in compliant actors and providers.
   
   Since wRPC (#1389)
   enabled  wasmCloud 1.0 is going to be WIT-first going forward, all
   WIT-driven function executions have access to the relevant
   interface (WIT interfaces, rather than Smithy-derived ones) that they
   call, at call time.
   
   Given that actor & provider side function executions have access to
   their WIT interfaces (ex. `wasi:keyvalue/readwrite.get`), what we need
   to do is differentiate between the case where *multiple targets*
   might be responding to the same WIT interface-backed invocations.
   
   Unlike before, `set-target` only needs to really differentiate between *link
   names*.
   
   This commit updates `set-target` to perform differentiate between link
   names, building on the work already done to introduce more opaque
   targeting via Component IDs.
 - <csr-id-5d1590e231f75e4d418a5115b3449dda0dadec9a/> record polyfilled component imports
 - <csr-id-18875a7264ec4b8c0a82f3389be72267be202e58/> fix custom interface support and tests
 - <csr-id-fec6f5f1372a1de5737f5ec585ad735e14c20480/> remove module support
 - <csr-id-219342386861f21fab64429cad4f8e88ae679c0a/> add resource handling stubs
 - <csr-id-eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a/> support composite types
 - <csr-id-da6e2b3a91013c8564c22f8305d665aec78a072d/> support composite Wasmtime type reflection in polyfills
 - <csr-id-713e7746a9aa61ceff373cf62cf85e68617fa788/> add (most of) custom interface plumbing
 - <csr-id-64d21b1f3d413e4c5da78d8045c1366c3782a190/> Adds some additional context around test failures I was seeing
 - <csr-id-1a048a71320dbbf58f331e7e958f4b1cd5ed4537/> Adds support for actor config
   This is a fairly large PR because it is adding several new control interface
   topics as well as actually adding the actor config feature.
   
   This feature was motivated by 2 major reasons:
   
   1. We have been needing something like this for a while, at the very least for
   being able to configure link names in an actor at runtime
2. There aren't currently any active (yes there were some in the past) efforts
      to add a generic `wasi:cloud/guest-config` interface that can allow any host
      to provide config values to a component. I want to use this as a springboard
      for the conversation in wasi-cloud as we will start to use it and can give
      active feedback as to how the interface should be shaped
- make claims optional (at least for now)
- add streaming support to `wasmcloud:bus`
- rename `wasmcloud_host` -> `wasmcloud_runtime`
- remove all `wasmcloud-interface-*` usages
- add support for `command` executables (I/O actors)
- add local lattice proving the concept, which is used for testing of the feature
- implement an actor instance pool

### Bug Fixes

<csr-id-fa1fde185b47b055e511f6f2dee095e269db1651/>
<csr-id-61308b7827789d442b2508ba5347add03bdbb069/>
<csr-id-7abc17038655db16e71471edd2cc7dc0a760b6ac/>
<csr-id-4ed38913f19fcd4dd44dfdcc9007e80e80cdc960/>
<csr-id-ccb3c73dc1351b11233896abc068a200374df079/>
<csr-id-bff9816db3193c57ccfe48852f21258a8430530e/>
<csr-id-c8f26b84346600870f62df05238f64421c6e66c6/>
<csr-id-149f98b60c1e70d0e68153add3e30b8fb4483e11/>
<csr-id-0f6a1eb97cb46a43c9b24977a8e8dc11061af330/>
<csr-id-d1c3a599377ccb46ba11f2d9484812dc2a67b22c/>
<csr-id-923c650cc4b58e5316e53ae8141219de15862d34/>
<csr-id-e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12/>
<csr-id-542427e4a0bff82c25ffe35c9587f34783a207dd/>
<csr-id-c6fa704f001a394c10f8769d670941aff62d6414/>
<csr-id-7db1183dbe84aeeb1967eb28d71876f6f175c2c2/>
<csr-id-1d3fd96f2fe23c71b2ef70bb5199db8009c56154/>
<csr-id-c555bab75cdc6f2953ec394b4fe41133d83efb66/>
<csr-id-1829b27213e836cb347a542e9cdc771c74427892/>
<csr-id-b13a50ca8b882fe5142f9ad26501ffeba47af24c/>
<csr-id-a82847f4e4a2637bc9d6f9c75be0a902f7944212/>

 - <csr-id-4da0105ac7bf463eeb79bc3047cb5e92664f8a7c/> rework `wasi:http` error handling
 - <csr-id-853105c8ad06b92686589b669765bbdbd439ccbc/> Ensures we have the proper limits set for max components
   It turns out that there are a bunch of other settings that we could have
   hit the limit on that we needed to set. These new settings are all set
   to the same as max components because you could have that number of
   individual components that would each have their own core module and
   stack.
   
   I tested this under load to make sure it actually works
 - <csr-id-726dd689e6d64eb44930834425d69f21cefc61cd/> log handling errors
 - <csr-id-8f0e15e01732e873e5861b1336254e21eafa0f10/> additional static instances
 - <csr-id-b014263cf3614995f597336bb40e51ab72bfa1c9/> setup debug traces
   This commit contains experimental code used to debug/replicate the
   o11y traces for making a call with http-client & http-provider.
   
   Running this requires the following hackery:
   
   - running the docker compose for o11y
- (re) building dog-fetcher
- modifying the WADM w/ dog fetcher (done by this commit)
- build & create PAR for http-client
- build & create PAR for http-server
- set WASMCLOUD_OVERRIDE_TRACES_ENDPOINT before `wash up`
- replacing existing wasmcloud host (in `~/.wash/downloads/v1.0.2`)
- Adds missing implementation to bindgen for provider -> actor invocations
- Uncomments implementation from the host for wasmcloud:messaging
- Adds an invoker component that reacts to messaging rather than HTTP
- Uses messaging & keyvalue providers plus the actor in a single test

### Other

 - <csr-id-b96a9bf8544c7ae6459971acff75865e8ab886bd/> wasmcloud-runtime v0.3.0
 - <csr-id-1af6e05f1a47be4e62a4c21d1704aff2e09bef89/> bump wasmcloud-core v0.10.0, safety bump 5 crates
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-tracing v0.8.0, wasmcloud-provider-sdk v0.9.0, wash-cli v0.33.0, wash-lib v0.26.0
 - <csr-id-d8f73f56a3ebb67ddb34acb6598039c51c05e772/> wasmcloud-runtime v0.2.0
 - <csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/> wasmcloud-runtime v0.1.0
 - <csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/> bump for test-util release
   Bump wasmcloud-core v0.8.0, opentelemetry-nats v0.1.1, provider-archive v0.12.0, wasmcloud-runtime v0.3.0, wasmcloud-secrets-types v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, safety bump 8 crates
   
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, wasmcloud-provider-sdk v0.7.0, wash-cli v0.30.0, wash-lib v0.23.0
 - <csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/> improve documentation
 - <csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/> clarify the instance exclusions
 - <csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/> update to Wasmtime 18
 - <csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/> update to wasmtime 17
 - <csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/> update to wasmtime 16
   Note this uses a release branch as 16 is not out yet.
 - <csr-id-a278764abaac2b745b833aaea8e041e357b97a15/> pin blobstore to upstream rev
   Pin until https://github.com/WebAssembly/wasi-blob-store/pull/14 merged
 - <csr-id-d16324054a454347044f7cc052da1bbd4324a284/> bump crate versions
 - <csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/> bump to `0.79.0`
 - <csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/> update dependencies
 - <csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/> switch to upstream `wasi:blobstore`
 - <csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/> update WIT dependencies
 - <csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/> update to Wasmtime 12
 - <csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/> update WIT dependencies
   This fixes `poll-oneof` mismatch
 - <csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/> update dependencies

### Refactor

 - <csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/> use upstream preview1 adapter crate
 - <csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/> extract and document `InvocationStream` type
 - <csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/> wascap::jwt::Actor -> wascap::jwt::Component
 - <csr-id-e1281733c73988686a499d43e808e4cd11fd5759/> link actors on creation
 - <csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/> improve WASI linking error
 - <csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/> remove instance pooling
 - <csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/> reduce verbosity on actor logs
 - <csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/> component instantiation error message
 - <csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/> split interface implementations into separate modules

### Test

 - <csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/> replicate component test in modules and compat

### New Features (BREAKING)

 - <csr-id-fc1bbf45e212b2d00b654a27a38a7322e8889be6/> increase wasm memory limit, 256MiB
 - <csr-id-2c0b5860390373720845cc2060705ad7d942a3c3/> implement streaming in wasi:blobstore
 - <csr-id-f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71/> allow tuning runtime parameters
 - <csr-id-acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5/> add secrets store/reveal imports
 - <csr-id-6b2e1b5915a0e894a567622ffc193230e5654c1f/> Removes old guest config and uses runtime config instead
   Most of the changes are related to wit updates, but this removes the
   guest config from `wasmcloud:bus` and pulls down `wasi:config` in its
   place
 - <csr-id-91874e9f4bf2b37b895a4654250203144e12815c/> convert to `wrpc:blobstore`
 - <csr-id-716d251478cf174085f6ff274854ddebd9e0d772/> use `wasmcloud:messaging` in providers
   Also implement statically invoking the `handler` on components in the
   host
 - <csr-id-5af1138da6afa3ca6424d4ff10aa49211952c898/> support interface link put, component spec
 - <csr-id-42d069eee87d1b5befff1a95b49973064f1a1d1b/> Updates topics to the new standard
   This is a wide ranging PR that changes all the topics as described
   in #1108. This also involved removing the start and stop actor
   operations. While I was in different parts of the code I did some small
   "campfire rule" cleanups mostly of clippy lints and removal of
   clippy pedant mode.

<csr-unknown>
With that said, note that this is only going to be added for actors built againstthe component model. Since this is net new functionality, I didn’t think it wasworth it to try to backport.As for testing, I have tested that an actor can import the functions and get the valuesvia the various e2e tests and also manually validated that all of the new topicswork. implement wasifills for simple types implement outgoing HTTP add support for call aliases support chunking and dechunking of requests implement wasi:blobstore partially implement wasi:keyvalue/atomic implement wasmcloud:http/incoming-handler support move builtin smithy structs to compat implement link names and a2a calls implement wasmcloud:messaging/consumer support implement wasi:keyvalue/readwrite support introduce Blobstore trait implement actor -> provider linking provide wasmCloud interface stubs implement linkdef add/delete implement data streaming propagate traces through components Fixes issue with running runtime on smaller hostsWe found that on hosts with less then 2GB of memory (give or take alittle) the host would fail to start when the pooling allocator startedallocating virtual memory. You could get around this by settingvm_overcommit to 1 or 2, but this is not the best experience for thoserunning in production. This fixes the issue by falling back to thedynamic memory allocator if setup fails.We already have a plan to add some more of these tunables as optionsfor the host, but those will be added in future PRs as a feature add rustdoc spelling fix link_name functionality, reorganize tests correct name and data streaming, update WIT do not polyfill wasi:blobstore interfaces do not polyfill wasi cloud interfaces improve target lookup error handling add messaging triggered test actorThis commit is the culmination of a few things that were required forgetting our flavor of E2E tests (in the top level tests/ dir)working for a Provider & Actor.This commit is quite large because it does many things:With this, we have an easy to understand way to test every providerthat we have in the repository. do not polyfill logging tone down instrumentation level bindgen issues preventing buildsThis commit fixes the provider bindgen issues for non http-serverbuilds (ex. kv-redis) parse package fix clippy warning, added ; for consistency, return directly the instance instead of wrapping the instance’s components in a future Add comments, remove useless future::ready fmt return Ready on trailers allow namespaces with slashes properly handle path_with_query switch to wasmCloud messaging WIT<csr-unknown/>

## 0.3.0 (2024-09-28)

<csr-id-955a6893792e86292883e76de57434616c28d380/>
<csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/>
<csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/>
<csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/>
<csr-id-5e4572379d370de74dad4b393746fee242e374f2/>
<csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/>
<csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/>
<csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/>
<csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/>
<csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/>
<csr-id-22e71e59be566136f6028393153827662ec9f68e/>
<csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/>
<csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/>
<csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/>
<csr-id-089b8955d309b1cab3eaa45f03d394656deada55/>
<csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/>
<csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/>
<csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/>
<csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/>
<csr-id-2389f27f0b570164a895a37abd462be2d68f20be/>
<csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/>
<csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/>
<csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/>
<csr-id-0023f7e86d5a40a534f623b7220743f27871549e/>
<csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/>
<csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/>
<csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/>
<csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/>
<csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/>
<csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/>
<csr-id-a278764abaac2b745b833aaea8e041e357b97a15/>
<csr-id-d16324054a454347044f7cc052da1bbd4324a284/>
<csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/>
<csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/>
<csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/>
<csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/>
<csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/>
<csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/>
<csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/>
<csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/>
<csr-id-e1281733c73988686a499d43e808e4cd11fd5759/>
<csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/>
<csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/>
<csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/>
<csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/>
<csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/>
<csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/>
<csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/>
<csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/>
<csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/>
<csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/>
<csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/>
<csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/>
<csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/>
<csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/>
<csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/>
<csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/>
<csr-id-e7c30405302fcccc612209335179f0bc47d8e996/>
<csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/>
<csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/>
<csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/>
<csr-id-1af6e05f1a47be4e62a4c21d1704aff2e09bef89/>
<csr-id-d8f73f56a3ebb67ddb34acb6598039c51c05e772/>
<csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/>
<csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/>
<csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/>
<csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/>

### Chore

 - <csr-id-955a6893792e86292883e76de57434616c28d380/> update `messaging` to `0.2.0`
 - <csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/> reenable `clippy::pedantic`
 - <csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/> remove unused dependencies
 - <csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/> remove compat crate
 - <csr-id-5e4572379d370de74dad4b393746fee242e374f2/> update WIT dependencies
 - <csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/> move CallTargetInterface to core
 - <csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/> simplify error handling
 - <csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/> fix clippy lints
 - <csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/> integrate set-link-name and wrpc
 - <csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/> remove `Actor` abstraction
 - <csr-id-22e71e59be566136f6028393153827662ec9f68e/> import `wrpc-runtime-wasmtime`
 - <csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/> remove `wit-component` dep
   Ciao
 - <csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/> appease Clippy
   Chillax, Clip
 - <csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/> switch wasi-keyvalue to `main`
 - <csr-id-089b8955d309b1cab3eaa45f03d394656deada55/> fix `wasi-keyvalue` incoming value ownership mismatch
 - <csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/> implement preview 2 interfaces
 - <csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/> update WIT packages
 - <csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/> remove logging `with` pin
 - <csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/> update to Wasmtime 15
 - <csr-id-2389f27f0b570164a895a37abd462be2d68f20be/> polish tracing and logging levels
 - <csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/> integrate `wash` into the workspace
 - <csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/> update to Wasmtime 14 and latest WIT
 - <csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/> resolve 1.73.0 warnings
 - <csr-id-0023f7e86d5a40a534f623b7220743f27871549e/> reduce verbosity of instrumented functions
 - <csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/> mark non-exhaustive Debug impls as such
 - <csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/> remove noisy fields from instruments

### Refactor

 - <csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/> use upstream preview1 adapter crate

### Other

 - <csr-id-1af6e05f1a47be4e62a4c21d1704aff2e09bef89/> bump wasmcloud-core v0.10.0, safety bump 5 crates
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-tracing v0.8.0, wasmcloud-provider-sdk v0.9.0, wash-cli v0.33.0, wash-lib v0.26.0
 - <csr-id-d8f73f56a3ebb67ddb34acb6598039c51c05e772/> wasmcloud-runtime v0.2.0
 - <csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/> wasmcloud-runtime v0.1.0
 - <csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/> bump for test-util release
   Bump wasmcloud-core v0.8.0, opentelemetry-nats v0.1.1, provider-archive v0.12.0, wasmcloud-runtime v0.3.0, wasmcloud-secrets-types v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, safety bump 8 crates
   
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, wasmcloud-provider-sdk v0.7.0, wash-cli v0.30.0, wash-lib v0.23.0

### Chore

 - <csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/> allow complex types
 - <csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/> update component/runtime/host crate READMEs

### Refactor

 - <csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/> extract and document `InvocationStream` type

### Other

 - <csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/> improve documentation

### Chore

 - <csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/> increase max memory size to 10mb
   This commit increases the max memory that can be addressed by a single
   component to 10mb.
 - <csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/> update wRPC
 - <csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/> remove unused logging exports
 - <csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/> address clippy warnings
 - <csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/> update to stream-based serving
 - <csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/> Replace actor reference by component in runtime crate
 - <csr-id-e7c30405302fcccc612209335179f0bc47d8e996/> improve error messages for missing links
   When known interfaces are accessed, we show a message that notes that
   the target is unknown, but we can improve on that by alerting the user
   to a possibly missing link.
 - <csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/> Replace actor references by component in crates
   Rename wash-cli wash-build tests name and references
   
   Fix nix flake path to Cargo.lock file
   
   Fix format
   
   Rename in wash-cli tests
 - <csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/> generate changelogs after 1.0.1 release

### Chore

 - <csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/> updated with newest features

### Chore

 - <csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/> replace references to 'actor' with 'component'

### New Features

<csr-id-cfb66f81180a3b47d6e7df1a444a1ec945115b15/>
<csr-id-2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3/>
<csr-id-123cb2f9b8981c37bc333fece71c009ce875e30f/>
<csr-id-813ce52a9c11270814eec051dfaa8817bf9f567d/>
<csr-id-bef159ab4d5ce6ba73e7c3465110c2990da64eac/>
<csr-id-d434e148620d394856246ac34bb0a64c37181970/>
<csr-id-50d0ed1086c5f417ed64dcce139cc3c2b50ca14c/>
<csr-id-54f0afa7b7d67b658113eb2a7ea667b77ea4bd55/>
<csr-id-2e3bd2bd7611e5de9fe123f53778f282613eb0de/>
<csr-id-77d663d3e1fd5590177ac8003a313a3edf29ab1f/>
<csr-id-02c1ddc0d62b40f63afe4d270643ebc3bf39c081/>
<csr-id-9eda090fe6d790f239093738515570a7886eae8d/>
<csr-id-4de853a1d3e28126faf9efa51aaa97714af7b493/>
<csr-id-3ae7cce621b4be163feac7be903f3ff66f40ddc3/>
<csr-id-e943eca7512a0d96a617451e2e2af78718d0f685/>
<csr-id-7364dd8afae5c8884ca923b39c5680c60d8d0e3d/>

 - <csr-id-9cd2b4034f8d5688ce250429dc14120eaf61b483/> update `wrpc:keyvalue` in providers
   part of this process is adopting `wit-bindgen-wrpc` in the host
 - <csr-id-a1754195fca5a13c8cdde713dad3e1a9765adaf5/> update `wasi:keyvalue`
 - <csr-id-2352092930b50992e47e7fcf013ae5f084bf2a8e/> Bumps our wasmcloud wit to 1.0
   This bumps our main `wasmcloud:bus` package and the package in the `runtime`
   crate to 1.0.0 in preparation for release. Also removes the use of
   the wasmcloud interface in tests where it wasn't needed
 - <csr-id-023358b41b154e75a737f10f652e197dfa6b0093/> update to wasmtime 19
 - <csr-id-f56492ac6b5e6f1274a1f11b061c42cace372122/> migrate to `wrpc:keyvalue`
 - <csr-id-383b3f3067dddc913d5a0c052f7bbb9c47fe8663/> implement `wrpc:blobstore/blobstore` for FS
 - <csr-id-614af7e3ed734c56b27cd1d2aacb0789a85e8b81/> implement Redis `wrpc:keyvalue/{atomic,eventual}`
 - <csr-id-e0dac9de4d3a74424e3138971753db9da143db5a/> implement `wasi:http/outgoing-handler` provider
 - <csr-id-0c5aee7621f01f6a3a90322c55836f45184df79a/> support p1 module execution
 - <csr-id-76c1ed7b5c49152aabd83d27f0b8955d7f874864/> support pubsub on wRPC subjects
   Up until now, publishing and subscribing for RPC communcations on the
   NATS cluster happened on subjects that were related to the wasmbus
   protocol (i.e. 'wasmbus.rpc.*').
   
   To support the WIT-native invocations, i.e. wRPC (#1389), we must
   change the publication and subscription subjects to include also the
   subjects that are expected to be used by wprc.
   
   This commit updates the provider-sdk to listen *additionally* to
   subjects that are required/used by wrpc, though we do not yet have an
   implementation for encode/deocde.
 - <csr-id-590a49477d5832ec99f3b2e251813d51b4abb274/> Switches runtime config to use a pooling allocator
   This leads to significant performance increases on Linux and brings it
   up to the same performance levels as other operating systems
 - <csr-id-400802ac767a06459fc1d93c3ab5cd4223e8506f/> improve byte stream efficiency
 - <csr-id-25e3e51d7e123aae3e3681886d2e095b29202b94/> Switches modules to use pre instantiation instead
   In my load testing of this locally, this led to a 20% increase in throughput
 - <csr-id-f2223a3f5378c3cebfec96b5322df619fcecc556/> implement `wrpc:http/incoming-handler`
 - <csr-id-0c0c004bafb60323018fc1c86cb13493f72d29cd/> switch to `wrpc` for `wasmcloud:messaging`
 - <csr-id-5ede01b1fe0bc62234d2b7d6c72775d9e248a130/> switch to `wrpc:{keyvalue,blobstore}`
 - <csr-id-246384524cfe65ce6742558425b885247b461c5c/> implement `wrpc:http/outgoing-handler.handle`
 - <csr-id-5d19ba16a98dca9439628e8449309ccaa763ab10/> change set-target to set-link-name
   Up until the relatively low-level `wasmcloud:bus/lattice` WIT
   interface has used a function called `set-target` to aim invocations
   that occurred in compliant actors and providers.
   
   Since wRPC (#1389)
   enabled  wasmCloud 1.0 is going to be WIT-first going forward, all
   WIT-driven function executions have access to the relevant
   interface (WIT interfaces, rather than Smithy-derived ones) that they
   call, at call time.
   
   Given that actor & provider side function executions have access to
   their WIT interfaces (ex. `wasi:keyvalue/readwrite.get`), what we need
   to do is differentiate between the case where *multiple targets*
   might be responding to the same WIT interface-backed invocations.
   
   Unlike before, `set-target` only needs to really differentiate between *link
   names*.
   
   This commit updates `set-target` to perform differentiate between link
   names, building on the work already done to introduce more opaque
   targeting via Component IDs.
 - <csr-id-5d1590e231f75e4d418a5115b3449dda0dadec9a/> record polyfilled component imports
 - <csr-id-18875a7264ec4b8c0a82f3389be72267be202e58/> fix custom interface support and tests
 - <csr-id-fec6f5f1372a1de5737f5ec585ad735e14c20480/> remove module support
 - <csr-id-219342386861f21fab64429cad4f8e88ae679c0a/> add resource handling stubs
 - <csr-id-eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a/> support composite types
 - <csr-id-da6e2b3a91013c8564c22f8305d665aec78a072d/> support composite Wasmtime type reflection in polyfills
 - <csr-id-713e7746a9aa61ceff373cf62cf85e68617fa788/> add (most of) custom interface plumbing
 - <csr-id-64d21b1f3d413e4c5da78d8045c1366c3782a190/> Adds some additional context around test failures I was seeing
 - <csr-id-1a048a71320dbbf58f331e7e958f4b1cd5ed4537/> Adds support for actor config
   This is a fairly large PR because it is adding several new control interface
   topics as well as actually adding the actor config feature.
   
   This feature was motivated by 2 major reasons:
   
   1. We have been needing something like this for a while, at the very least for
   being able to configure link names in an actor at runtime
2. There aren't currently any active (yes there were some in the past) efforts
      to add a generic `wasi:cloud/guest-config` interface that can allow any host
      to provide config values to a component. I want to use this as a springboard
      for the conversation in wasi-cloud as we will start to use it and can give
      active feedback as to how the interface should be shaped
- make claims optional (at least for now)
- add streaming support to `wasmcloud:bus`
- rename `wasmcloud_host` -> `wasmcloud_runtime`
- remove all `wasmcloud-interface-*` usages
- add support for `command` executables (I/O actors)
- add local lattice proving the concept, which is used for testing of the feature
- implement an actor instance pool
 - <csr-id-cda9f724d2d2e4ea55006a43b166d18875148c48/> generate crate changelogs
 - <csr-id-e928020fd774abcc213fec560d89f128464da319/> limit max execution time to 10 minutes
 - <csr-id-33b50c2d258ca9744ed65b153a6580f893172e0c/> update to Wasmtime 20
 - <csr-id-f986e39450676dc598b92f13cb6e52b9c3200c0b/> generate crate changelogs
 - <csr-id-3eb453405aa144599f43bbaf56197566c9f0cf0a/> count epoch in a separate OS thread
 - <csr-id-a66921edd9be3202d1296a165c34faf597b1dec1/> propagate `max_execution_time` to the runtime
 - <csr-id-070751231e5bb4891b995e992e5206b3050ecc30/> pass original component instance through the context
 - <csr-id-9cb1b784fe7a8892d73bdb40d1172b1879fcd932/> upgrade `wrpc`, `async-nats`, `wasmtime`
 - <csr-id-a5f9432845bcb7c8f423776fd56ef4a735fe43c7/> add `TargetEntity::lattice_id()`
 - <csr-id-077a28a6567a436c99368c7eb1bd5dd2a6bc6103/> gracefully shutdown epoch interrupt thread
 - <csr-id-f5093226a252c35be1ea1e9ed9740923f33ec015/> update to WASI 0.2.1
 - <csr-id-c37c92abf8c93a40f8174c588e83b5242dcbc4c5/> update to wasmtime 25
 - <csr-id-8575f732df33ca973ff340fc3e4bc7fbfeaf89f3/> Adds support for batch support to the host
   This enables keyvalue batch support inside of the host, along with a test
   to make sure it works. Not all of our providers implement batch yet, so
   this uses the Redis provider, which did have implementions. I did have to
   fix the redis provider to get the right type of data back and transform
   it. I also had to update our wRPC versions so we could pick up on some
   bug fixes for the types we are encoding in the batch interface.
 - <csr-id-056b57e50cfc13ecd863f54d30032988bd23d94b/> enable wasmtime gc feature
 - <csr-id-26d7f64659dbf3263f36da92df89003c579077cc/> fallback to `wrpc:blobstore@0.1.0`
 - <csr-id-156d3f39e6775ec6aea3a1eb864bf7c893749e07/> update to Wasmtime 23

### Bug Fixes

<csr-id-d1c3a599377ccb46ba11f2d9484812dc2a67b22c/>
<csr-id-923c650cc4b58e5316e53ae8141219de15862d34/>
<csr-id-e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12/>
<csr-id-542427e4a0bff82c25ffe35c9587f34783a207dd/>
<csr-id-c6fa704f001a394c10f8769d670941aff62d6414/>
<csr-id-7db1183dbe84aeeb1967eb28d71876f6f175c2c2/>
<csr-id-1d3fd96f2fe23c71b2ef70bb5199db8009c56154/>
<csr-id-c555bab75cdc6f2953ec394b4fe41133d83efb66/>
<csr-id-1829b27213e836cb347a542e9cdc771c74427892/>
<csr-id-b13a50ca8b882fe5142f9ad26501ffeba47af24c/>
<csr-id-a82847f4e4a2637bc9d6f9c75be0a902f7944212/>
<csr-id-b014263cf3614995f597336bb40e51ab72bfa1c9/>
<csr-id-fa1fde185b47b055e511f6f2dee095e269db1651/>
<csr-id-61308b7827789d442b2508ba5347add03bdbb069/>
<csr-id-4da0105ac7bf463eeb79bc3047cb5e92664f8a7c/>
<csr-id-853105c8ad06b92686589b669765bbdbd439ccbc/>
<csr-id-726dd689e6d64eb44930834425d69f21cefc61cd/>
<csr-id-8f0e15e01732e873e5861b1336254e21eafa0f10/>

 - <csr-id-7abc17038655db16e71471edd2cc7dc0a760b6ac/> rustdoc spelling
 - <csr-id-4ed38913f19fcd4dd44dfdcc9007e80e80cdc960/> fix `link_name` functionality, reorganize tests
 - <csr-id-ccb3c73dc1351b11233896abc068a200374df079/> correct name and data streaming, update WIT
 - <csr-id-bff9816db3193c57ccfe48852f21258a8430530e/> do not polyfill wasi:blobstore interfaces
 - <csr-id-c8f26b84346600870f62df05238f64421c6e66c6/> do not polyfill wasi cloud interfaces
 - <csr-id-149f98b60c1e70d0e68153add3e30b8fb4483e11/> improve target lookup error handling
 - <csr-id-0f6a1eb97cb46a43c9b24977a8e8dc11061af330/> add messaging triggered test actor
   This commit is the culmination of a few things that were required for
   getting our flavor of E2E tests (in the top level `tests/` dir)
   working for a Provider & Actor.
   
   This commit is quite large because it does many things:
   
   - Adds missing implementation to bindgen for provider -> actor invocations

### Other

 - <csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/> clarify the instance exclusions
 - <csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/> update to Wasmtime 18
 - <csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/> update to wasmtime 17
 - <csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/> update to wasmtime 16
   Note this uses a release branch as 16 is not out yet.
 - <csr-id-a278764abaac2b745b833aaea8e041e357b97a15/> pin blobstore to upstream rev
   Pin until https://github.com/WebAssembly/wasi-blob-store/pull/14 merged
 - <csr-id-d16324054a454347044f7cc052da1bbd4324a284/> bump crate versions
 - <csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/> bump to `0.79.0`
 - <csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/> update dependencies
 - <csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/> switch to upstream `wasi:blobstore`
 - <csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/> update WIT dependencies
 - <csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/> update to Wasmtime 12
 - <csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/> update WIT dependencies
   This fixes `poll-oneof` mismatch
 - <csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/> update dependencies

### Refactor

 - <csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/> wascap::jwt::Actor -> wascap::jwt::Component
 - <csr-id-e1281733c73988686a499d43e808e4cd11fd5759/> link actors on creation
 - <csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/> improve WASI linking error
 - <csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/> remove instance pooling
 - <csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/> reduce verbosity on actor logs
 - <csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/> component instantiation error message
 - <csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/> split interface implementations into separate modules

### Test

 - <csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/> replicate component test in modules and compat

### New Features (BREAKING)

 - <csr-id-6b2e1b5915a0e894a567622ffc193230e5654c1f/> Removes old guest config and uses runtime config instead
   Most of the changes are related to wit updates, but this removes the
   guest config from `wasmcloud:bus` and pulls down `wasi:config` in its
   place
 - <csr-id-91874e9f4bf2b37b895a4654250203144e12815c/> convert to `wrpc:blobstore`
 - <csr-id-716d251478cf174085f6ff274854ddebd9e0d772/> use `wasmcloud:messaging` in providers
   Also implement statically invoking the `handler` on components in the
   host
 - <csr-id-5af1138da6afa3ca6424d4ff10aa49211952c898/> support interface link put, component spec
 - <csr-id-42d069eee87d1b5befff1a95b49973064f1a1d1b/> Updates topics to the new standard
   This is a wide ranging PR that changes all the topics as described
   in #1108. This also involved removing the start and stop actor
   operations. While I was in different parts of the code I did some small
   "campfire rule" cleanups mostly of clippy lints and removal of
   clippy pedant mode.
 - <csr-id-acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5/> add secrets store/reveal imports
 - <csr-id-fc1bbf45e212b2d00b654a27a38a7322e8889be6/> increase wasm memory limit, 256MiB
 - <csr-id-2c0b5860390373720845cc2060705ad7d942a3c3/> implement streaming in wasi:blobstore
 - <csr-id-f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71/> allow tuning runtime parameters

<csr-unknown>
<csr-unknown>
 rework wasi:http error handling Ensures we have the proper limits set for max componentsIt turns out that there are a bunch of other settings that we could havehit the limit on that we needed to set. These new settings are all setto the same as max components because you could have that number ofindividual components that would each have their own core module andstack.I tested this under load to make sure it actually works log handling errors additional static instances<csr-unknown/>
<csr-unknown/>

## 0.2.0 (2024-09-06)

<csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/>
<csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/>
<csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/>
<csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/>
<csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/>
<csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/>
<csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/>
<csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/>
<csr-id-e7c30405302fcccc612209335179f0bc47d8e996/>
<csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/>
<csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/>
<csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/>
<csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/>
<csr-id-955a6893792e86292883e76de57434616c28d380/>
<csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/>
<csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/>
<csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/>
<csr-id-5e4572379d370de74dad4b393746fee242e374f2/>
<csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/>
<csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/>
<csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/>
<csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/>
<csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/>
<csr-id-22e71e59be566136f6028393153827662ec9f68e/>
<csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/>
<csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/>
<csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/>
<csr-id-089b8955d309b1cab3eaa45f03d394656deada55/>
<csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/>
<csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/>
<csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/>
<csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/>
<csr-id-2389f27f0b570164a895a37abd462be2d68f20be/>
<csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/>
<csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/>
<csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/>
<csr-id-0023f7e86d5a40a534f623b7220743f27871549e/>
<csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/>
<csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/>
<csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/>
<csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/>
<csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/>
<csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/>
<csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/>
<csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/>
<csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/>
<csr-id-a278764abaac2b745b833aaea8e041e357b97a15/>
<csr-id-d16324054a454347044f7cc052da1bbd4324a284/>
<csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/>
<csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/>
<csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/>
<csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/>
<csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/>
<csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/>
<csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/>
<csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/>
<csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/>
<csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/>
<csr-id-e1281733c73988686a499d43e808e4cd11fd5759/>
<csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/>
<csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/>
<csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/>
<csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/>
<csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/>
<csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/>

### Chore

 - <csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/> allow complex types
 - <csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/> update component/runtime/host crate READMEs
 - <csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/> increase max memory size to 10mb
   This commit increases the max memory that can be addressed by a single
   component to 10mb.
 - <csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/> update wRPC
 - <csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/> remove unused logging exports
 - <csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/> address clippy warnings
 - <csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/> update to stream-based serving
 - <csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/> Replace actor reference by component in runtime crate
 - <csr-id-e7c30405302fcccc612209335179f0bc47d8e996/> improve error messages for missing links
   When known interfaces are accessed, we show a message that notes that
   the target is unknown, but we can improve on that by alerting the user
   to a possibly missing link.
 - <csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/> Replace actor references by component in crates
   Rename wash-cli wash-build tests name and references
   
   Fix nix flake path to Cargo.lock file
   
   Fix format
   
   Rename in wash-cli tests
 - <csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/> generate changelogs after 1.0.1 release
 - <csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/> updated with newest features
 - <csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/> replace references to 'actor' with 'component'
 - <csr-id-955a6893792e86292883e76de57434616c28d380/> update `messaging` to `0.2.0`
 - <csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/> reenable `clippy::pedantic`
 - <csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/> remove unused dependencies
 - <csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/> remove compat crate
 - <csr-id-5e4572379d370de74dad4b393746fee242e374f2/> update WIT dependencies
 - <csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/> move CallTargetInterface to core
 - <csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/> simplify error handling
 - <csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/> fix clippy lints
 - <csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/> integrate set-link-name and wrpc
 - <csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/> remove `Actor` abstraction
 - <csr-id-22e71e59be566136f6028393153827662ec9f68e/> import `wrpc-runtime-wasmtime`
 - <csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/> remove `wit-component` dep
   Ciao
 - <csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/> appease Clippy
   Chillax, Clip
 - <csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/> switch wasi-keyvalue to `main`
 - <csr-id-089b8955d309b1cab3eaa45f03d394656deada55/> fix `wasi-keyvalue` incoming value ownership mismatch
 - <csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/> implement preview 2 interfaces
 - <csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/> update WIT packages
 - <csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/> remove logging `with` pin
 - <csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/> update to Wasmtime 15
 - <csr-id-2389f27f0b570164a895a37abd462be2d68f20be/> polish tracing and logging levels
 - <csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/> integrate `wash` into the workspace
 - <csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/> update to Wasmtime 14 and latest WIT
 - <csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/> resolve 1.73.0 warnings
 - <csr-id-0023f7e86d5a40a534f623b7220743f27871549e/> reduce verbosity of instrumented functions
 - <csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/> mark non-exhaustive Debug impls as such
 - <csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/> remove noisy fields from instruments

### New Features

<csr-id-cfb66f81180a3b47d6e7df1a444a1ec945115b15/>
<csr-id-2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3/>
<csr-id-123cb2f9b8981c37bc333fece71c009ce875e30f/>
<csr-id-813ce52a9c11270814eec051dfaa8817bf9f567d/>
<csr-id-bef159ab4d5ce6ba73e7c3465110c2990da64eac/>
<csr-id-d434e148620d394856246ac34bb0a64c37181970/>
<csr-id-50d0ed1086c5f417ed64dcce139cc3c2b50ca14c/>
<csr-id-54f0afa7b7d67b658113eb2a7ea667b77ea4bd55/>
<csr-id-2e3bd2bd7611e5de9fe123f53778f282613eb0de/>
<csr-id-77d663d3e1fd5590177ac8003a313a3edf29ab1f/>
<csr-id-02c1ddc0d62b40f63afe4d270643ebc3bf39c081/>
<csr-id-9eda090fe6d790f239093738515570a7886eae8d/>
<csr-id-4de853a1d3e28126faf9efa51aaa97714af7b493/>
<csr-id-3ae7cce621b4be163feac7be903f3ff66f40ddc3/>
<csr-id-e943eca7512a0d96a617451e2e2af78718d0f685/>
<csr-id-7364dd8afae5c8884ca923b39c5680c60d8d0e3d/>

 - <csr-id-056b57e50cfc13ecd863f54d30032988bd23d94b/> enable wasmtime gc feature
 - <csr-id-26d7f64659dbf3263f36da92df89003c579077cc/> fallback to `wrpc:blobstore@0.1.0`
 - <csr-id-156d3f39e6775ec6aea3a1eb864bf7c893749e07/> update to Wasmtime 23
 - <csr-id-070751231e5bb4891b995e992e5206b3050ecc30/> pass original component instance through the context
 - <csr-id-9cb1b784fe7a8892d73bdb40d1172b1879fcd932/> upgrade `wrpc`, `async-nats`, `wasmtime`
 - <csr-id-a5f9432845bcb7c8f423776fd56ef4a735fe43c7/> add `TargetEntity::lattice_id()`
 - <csr-id-077a28a6567a436c99368c7eb1bd5dd2a6bc6103/> gracefully shutdown epoch interrupt thread
 - <csr-id-f986e39450676dc598b92f13cb6e52b9c3200c0b/> generate crate changelogs
 - <csr-id-3eb453405aa144599f43bbaf56197566c9f0cf0a/> count epoch in a separate OS thread
 - <csr-id-a66921edd9be3202d1296a165c34faf597b1dec1/> propagate `max_execution_time` to the runtime
 - <csr-id-e928020fd774abcc213fec560d89f128464da319/> limit max execution time to 10 minutes
 - <csr-id-33b50c2d258ca9744ed65b153a6580f893172e0c/> update to Wasmtime 20
 - <csr-id-9cd2b4034f8d5688ce250429dc14120eaf61b483/> update `wrpc:keyvalue` in providers
   part of this process is adopting `wit-bindgen-wrpc` in the host
 - <csr-id-a1754195fca5a13c8cdde713dad3e1a9765adaf5/> update `wasi:keyvalue`
 - <csr-id-2352092930b50992e47e7fcf013ae5f084bf2a8e/> Bumps our wasmcloud wit to 1.0
   This bumps our main `wasmcloud:bus` package and the package in the `runtime`
   crate to 1.0.0 in preparation for release. Also removes the use of
   the wasmcloud interface in tests where it wasn't needed
 - <csr-id-023358b41b154e75a737f10f652e197dfa6b0093/> update to wasmtime 19
 - <csr-id-f56492ac6b5e6f1274a1f11b061c42cace372122/> migrate to `wrpc:keyvalue`
 - <csr-id-383b3f3067dddc913d5a0c052f7bbb9c47fe8663/> implement `wrpc:blobstore/blobstore` for FS
 - <csr-id-614af7e3ed734c56b27cd1d2aacb0789a85e8b81/> implement Redis `wrpc:keyvalue/{atomic,eventual}`
 - <csr-id-e0dac9de4d3a74424e3138971753db9da143db5a/> implement `wasi:http/outgoing-handler` provider
 - <csr-id-0c5aee7621f01f6a3a90322c55836f45184df79a/> support p1 module execution
 - <csr-id-76c1ed7b5c49152aabd83d27f0b8955d7f874864/> support pubsub on wRPC subjects
   Up until now, publishing and subscribing for RPC communcations on the
   NATS cluster happened on subjects that were related to the wasmbus
   protocol (i.e. 'wasmbus.rpc.*').
   
   To support the WIT-native invocations, i.e. wRPC (#1389), we must
   change the publication and subscription subjects to include also the
   subjects that are expected to be used by wprc.
   
   This commit updates the provider-sdk to listen *additionally* to
   subjects that are required/used by wrpc, though we do not yet have an
   implementation for encode/deocde.
 - <csr-id-590a49477d5832ec99f3b2e251813d51b4abb274/> Switches runtime config to use a pooling allocator
   This leads to significant performance increases on Linux and brings it
   up to the same performance levels as other operating systems
 - <csr-id-400802ac767a06459fc1d93c3ab5cd4223e8506f/> improve byte stream efficiency
 - <csr-id-25e3e51d7e123aae3e3681886d2e095b29202b94/> Switches modules to use pre instantiation instead
   In my load testing of this locally, this led to a 20% increase in throughput
 - <csr-id-f2223a3f5378c3cebfec96b5322df619fcecc556/> implement `wrpc:http/incoming-handler`
 - <csr-id-0c0c004bafb60323018fc1c86cb13493f72d29cd/> switch to `wrpc` for `wasmcloud:messaging`
 - <csr-id-5ede01b1fe0bc62234d2b7d6c72775d9e248a130/> switch to `wrpc:{keyvalue,blobstore}`
 - <csr-id-246384524cfe65ce6742558425b885247b461c5c/> implement `wrpc:http/outgoing-handler.handle`
 - <csr-id-5d19ba16a98dca9439628e8449309ccaa763ab10/> change set-target to set-link-name
   Up until the relatively low-level `wasmcloud:bus/lattice` WIT
   interface has used a function called `set-target` to aim invocations
   that occurred in compliant actors and providers.
   
   Since wRPC (#1389)
   enabled  wasmCloud 1.0 is going to be WIT-first going forward, all
   WIT-driven function executions have access to the relevant
   interface (WIT interfaces, rather than Smithy-derived ones) that they
   call, at call time.
   
   Given that actor & provider side function executions have access to
   their WIT interfaces (ex. `wasi:keyvalue/readwrite.get`), what we need
   to do is differentiate between the case where *multiple targets*
   might be responding to the same WIT interface-backed invocations.
   
   Unlike before, `set-target` only needs to really differentiate between *link
   names*.
   
   This commit updates `set-target` to perform differentiate between link
   names, building on the work already done to introduce more opaque
   targeting via Component IDs.
 - <csr-id-5d1590e231f75e4d418a5115b3449dda0dadec9a/> record polyfilled component imports
 - <csr-id-18875a7264ec4b8c0a82f3389be72267be202e58/> fix custom interface support and tests
 - <csr-id-fec6f5f1372a1de5737f5ec585ad735e14c20480/> remove module support
 - <csr-id-219342386861f21fab64429cad4f8e88ae679c0a/> add resource handling stubs
 - <csr-id-eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a/> support composite types
 - <csr-id-da6e2b3a91013c8564c22f8305d665aec78a072d/> support composite Wasmtime type reflection in polyfills
 - <csr-id-713e7746a9aa61ceff373cf62cf85e68617fa788/> add (most of) custom interface plumbing
 - <csr-id-64d21b1f3d413e4c5da78d8045c1366c3782a190/> Adds some additional context around test failures I was seeing
 - <csr-id-1a048a71320dbbf58f331e7e958f4b1cd5ed4537/> Adds support for actor config
   This is a fairly large PR because it is adding several new control interface
   topics as well as actually adding the actor config feature.
   
   This feature was motivated by 2 major reasons:
   
   1. We have been needing something like this for a while, at the very least for
   being able to configure link names in an actor at runtime
2. There aren't currently any active (yes there were some in the past) efforts
      to add a generic `wasi:cloud/guest-config` interface that can allow any host
      to provide config values to a component. I want to use this as a springboard
      for the conversation in wasi-cloud as we will start to use it and can give
      active feedback as to how the interface should be shaped
- make claims optional (at least for now)
- add streaming support to `wasmcloud:bus`
- rename `wasmcloud_host` -> `wasmcloud_runtime`
- remove all `wasmcloud-interface-*` usages
- add support for `command` executables (I/O actors)
- add local lattice proving the concept, which is used for testing of the feature
- implement an actor instance pool

### Bug Fixes

<csr-id-fa1fde185b47b055e511f6f2dee095e269db1651/>
<csr-id-61308b7827789d442b2508ba5347add03bdbb069/>
<csr-id-7abc17038655db16e71471edd2cc7dc0a760b6ac/>
<csr-id-4ed38913f19fcd4dd44dfdcc9007e80e80cdc960/>
<csr-id-ccb3c73dc1351b11233896abc068a200374df079/>
<csr-id-bff9816db3193c57ccfe48852f21258a8430530e/>
<csr-id-c8f26b84346600870f62df05238f64421c6e66c6/>
<csr-id-149f98b60c1e70d0e68153add3e30b8fb4483e11/>
<csr-id-0f6a1eb97cb46a43c9b24977a8e8dc11061af330/>
<csr-id-d1c3a599377ccb46ba11f2d9484812dc2a67b22c/>
<csr-id-923c650cc4b58e5316e53ae8141219de15862d34/>
<csr-id-e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12/>
<csr-id-542427e4a0bff82c25ffe35c9587f34783a207dd/>
<csr-id-c6fa704f001a394c10f8769d670941aff62d6414/>
<csr-id-7db1183dbe84aeeb1967eb28d71876f6f175c2c2/>
<csr-id-1d3fd96f2fe23c71b2ef70bb5199db8009c56154/>
<csr-id-c555bab75cdc6f2953ec394b4fe41133d83efb66/>
<csr-id-1829b27213e836cb347a542e9cdc771c74427892/>
<csr-id-b13a50ca8b882fe5142f9ad26501ffeba47af24c/>
<csr-id-a82847f4e4a2637bc9d6f9c75be0a902f7944212/>

 - <csr-id-b014263cf3614995f597336bb40e51ab72bfa1c9/> setup debug traces
   This commit contains experimental code used to debug/replicate the
   o11y traces for making a call with http-client & http-provider.
   
   Running this requires the following hackery:
   
   - running the docker compose for o11y

### Other

 - <csr-id-94adef8c3cbf722025d2c8ca990b264b24030b72/> wasmcloud-runtime v0.1.0
 - <csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/> bump for test-util release
   Bump wasmcloud-core v0.8.0, opentelemetry-nats v0.1.1, provider-archive v0.12.0, wasmcloud-runtime v0.3.0, wasmcloud-secrets-types v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, safety bump 8 crates
   
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, wasmcloud-provider-sdk v0.7.0, wash-cli v0.30.0, wash-lib v0.23.0
 - <csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/> improve documentation
 - <csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/> clarify the instance exclusions
 - <csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/> update to Wasmtime 18
 - <csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/> update to wasmtime 17
 - <csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/> update to wasmtime 16
   Note this uses a release branch as 16 is not out yet.
 - <csr-id-a278764abaac2b745b833aaea8e041e357b97a15/> pin blobstore to upstream rev
   Pin until https://github.com/WebAssembly/wasi-blob-store/pull/14 merged
 - <csr-id-d16324054a454347044f7cc052da1bbd4324a284/> bump crate versions
 - <csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/> bump to `0.79.0`
 - <csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/> update dependencies
 - <csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/> switch to upstream `wasi:blobstore`
 - <csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/> update WIT dependencies
 - <csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/> update to Wasmtime 12
 - <csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/> update WIT dependencies
   This fixes `poll-oneof` mismatch
 - <csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/> update dependencies

### Refactor

 - <csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/> use upstream preview1 adapter crate
 - <csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/> extract and document `InvocationStream` type
 - <csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/> wascap::jwt::Actor -> wascap::jwt::Component
 - <csr-id-e1281733c73988686a499d43e808e4cd11fd5759/> link actors on creation
 - <csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/> improve WASI linking error
 - <csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/> remove instance pooling
 - <csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/> reduce verbosity on actor logs
 - <csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/> component instantiation error message
 - <csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/> split interface implementations into separate modules

### Test

 - <csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/> replicate component test in modules and compat

### New Features (BREAKING)

 - <csr-id-fc1bbf45e212b2d00b654a27a38a7322e8889be6/> increase wasm memory limit, 256MiB
 - <csr-id-2c0b5860390373720845cc2060705ad7d942a3c3/> implement streaming in wasi:blobstore
 - <csr-id-f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71/> allow tuning runtime parameters
 - <csr-id-acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5/> add secrets store/reveal imports
 - <csr-id-6b2e1b5915a0e894a567622ffc193230e5654c1f/> Removes old guest config and uses runtime config instead
   Most of the changes are related to wit updates, but this removes the
   guest config from `wasmcloud:bus` and pulls down `wasi:config` in its
   place
 - <csr-id-91874e9f4bf2b37b895a4654250203144e12815c/> convert to `wrpc:blobstore`
 - <csr-id-716d251478cf174085f6ff274854ddebd9e0d772/> use `wasmcloud:messaging` in providers
   Also implement statically invoking the `handler` on components in the
   host
 - <csr-id-5af1138da6afa3ca6424d4ff10aa49211952c898/> support interface link put, component spec
 - <csr-id-42d069eee87d1b5befff1a95b49973064f1a1d1b/> Updates topics to the new standard
   This is a wide ranging PR that changes all the topics as described
   in #1108. This also involved removing the start and stop actor
   operations. While I was in different parts of the code I did some small
   "campfire rule" cleanups mostly of clippy lints and removal of
   clippy pedant mode.

<csr-unknown>
<csr-unknown>
(re) building dog-fetchermodifying the WADM w/ dog fetcher (done by this commit)build & create PAR for http-clientbuild & create PAR for http-serverset WASMCLOUD_OVERRIDE_TRACES_ENDPOINT before wash upreplacing existing wasmcloud host (in ~/.wash/downloads/v1.0.2)Adds missing implementation to bindgen for provider -> actor invocationsUncomments implementation from the host for wasmcloud:messagingAdds an invoker component that reacts to messaging rather than HTTPUses messaging & keyvalue providers plus the actor in a single test<csr-unknown>
With that said, note that this is only going to be added for actors built againstthe component model. Since this is net new functionality, I didn’t think it wasworth it to try to backport.As for testing, I have tested that an actor can import the functions and get the valuesvia the various e2e tests and also manually validated that all of the new topicswork. implement wasifills for simple types implement outgoing HTTP add support for call aliases support chunking and dechunking of requests implement wasi:blobstore partially implement wasi:keyvalue/atomic implement wasmcloud:http/incoming-handler support move builtin smithy structs to compat implement link names and a2a calls implement wasmcloud:messaging/consumer support implement wasi:keyvalue/readwrite support introduce Blobstore trait implement actor -> provider linking provide wasmCloud interface stubs implement linkdef add/delete implement data streaming propagate traces through components Fixes issue with running runtime on smaller hostsWe found that on hosts with less then 2GB of memory (give or take alittle) the host would fail to start when the pooling allocator startedallocating virtual memory. You could get around this by settingvm_overcommit to 1 or 2, but this is not the best experience for thoserunning in production. This fixes the issue by falling back to thedynamic memory allocator if setup fails.We already have a plan to add some more of these tunables as optionsfor the host, but those will be added in future PRs as a feature add rustdoc spelling fix link_name functionality, reorganize tests correct name and data streaming, update WIT do not polyfill wasi:blobstore interfaces do not polyfill wasi cloud interfaces improve target lookup error handling add messaging triggered test actorThis commit is the culmination of a few things that were required forgetting our flavor of E2E tests (in the top level tests/ dir)working for a Provider & Actor.This commit is quite large because it does many things:With this, we have an easy to understand way to test every providerthat we have in the repository. do not polyfill logging tone down instrumentation level bindgen issues preventing buildsThis commit fixes the provider bindgen issues for non http-serverbuilds (ex. kv-redis) parse package fix clippy warning, added ; for consistency, return directly the instance instead of wrapping the instance’s components in a future Add comments, remove useless future::ready fmt return Ready on trailers allow namespaces with slashes properly handle path_with_query switch to wasmCloud messaging WIT<csr-unknown/>
<csr-unknown/>
<csr-unknown/>

## 0.1.0 (2024-09-04)

<csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/>
<csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/>
<csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/>
<csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/>
<csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/>
<csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/>
<csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/>
<csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/>
<csr-id-e7c30405302fcccc612209335179f0bc47d8e996/>
<csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/>
<csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/>
<csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/>
<csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/>
<csr-id-955a6893792e86292883e76de57434616c28d380/>
<csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/>
<csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/>
<csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/>
<csr-id-5e4572379d370de74dad4b393746fee242e374f2/>
<csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/>
<csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/>
<csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/>
<csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/>
<csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/>
<csr-id-22e71e59be566136f6028393153827662ec9f68e/>
<csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/>
<csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/>
<csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/>
<csr-id-089b8955d309b1cab3eaa45f03d394656deada55/>
<csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/>
<csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/>
<csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/>
<csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/>
<csr-id-2389f27f0b570164a895a37abd462be2d68f20be/>
<csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/>
<csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/>
<csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/>
<csr-id-0023f7e86d5a40a534f623b7220743f27871549e/>
<csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/>
<csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/>
<csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/>
<csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/>
<csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/>
<csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/>
<csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/>
<csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/>
<csr-id-a278764abaac2b745b833aaea8e041e357b97a15/>
<csr-id-d16324054a454347044f7cc052da1bbd4324a284/>
<csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/>
<csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/>
<csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/>
<csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/>
<csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/>
<csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/>
<csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/>
<csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/>
<csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/>
<csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/>
<csr-id-e1281733c73988686a499d43e808e4cd11fd5759/>
<csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/>
<csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/>
<csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/>
<csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/>
<csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/>
<csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/>

### Chore

 - <csr-id-72cb5e7db4d3323f7b09beb7f4fc7754379929d0/> allow complex types
 - <csr-id-51c8ceb895b0069af9671e895b9f1ecb841ea6c3/> update component/runtime/host crate READMEs
 - <csr-id-3c414c52d4dfd31094b4cd2cee7e2f159cad639f/> increase max memory size to 10mb
   This commit increases the max memory that can be addressed by a single
   component to 10mb.
 - <csr-id-8fa3faad9fbb4b42ff7b8ea726c8cd4493b24a58/> update wRPC
 - <csr-id-40874d427a24c65746e18de44aef87cc4c3c4c13/> remove unused logging exports
 - <csr-id-bd50166619b8810ccdc2bcd80c33ff80d94bc909/> address clippy warnings
 - <csr-id-0f7093660a1ef09ff745daf5e1a96fd72c88984d/> update to stream-based serving
 - <csr-id-4bf428dbf693f1c91c276513e75b492e57d4d1a6/> Replace actor reference by component in runtime crate
 - <csr-id-e7c30405302fcccc612209335179f0bc47d8e996/> improve error messages for missing links
   When known interfaces are accessed, we show a message that notes that
   the target is unknown, but we can improve on that by alerting the user
   to a possibly missing link.
 - <csr-id-20c72ce0ed423561ae6dbd5a91959bec24ff7cf3/> Replace actor references by component in crates
   Rename wash-cli wash-build tests name and references
   
   Fix nix flake path to Cargo.lock file
   
   Fix format
   
   Rename in wash-cli tests
 - <csr-id-4e0313ae4cfb5cbb2d3fa0320c662466a7082c0e/> generate changelogs after 1.0.1 release
 - <csr-id-0f03f1f91210a4ed3fa64a4b07aebe8e56627ea6/> updated with newest features
 - <csr-id-7702e695cd9ab9436aaeb337373c3c1cb31f324a/> replace references to 'actor' with 'component'
 - <csr-id-955a6893792e86292883e76de57434616c28d380/> update `messaging` to `0.2.0`
 - <csr-id-327975d6a83bac3199240645b0c6a4a17cf00f66/> reenable `clippy::pedantic`
 - <csr-id-1bad246d9e174384c1a09bdff7e2dc88d911792e/> remove unused dependencies
 - <csr-id-f2aed15288300989aca03f899b095d3a71f8e5cd/> remove compat crate
 - <csr-id-5e4572379d370de74dad4b393746fee242e374f2/> update WIT dependencies
 - <csr-id-0d9002340ca8776c92a7d1e8b2caa4f804bb1bfb/> move CallTargetInterface to core
 - <csr-id-d61303d1b08b568ae4925120b1f36ed690d4b038/> simplify error handling
 - <csr-id-b83082ad1a065cd4c0ba08512471f9b3474df6dc/> fix clippy lints
 - <csr-id-4f55396a0340d65dbebdf6d4f0ca070d6f990fc4/> integrate set-link-name and wrpc
 - <csr-id-45445a6accd4d4322d192d201f315aa2ca2cb92b/> remove `Actor` abstraction
 - <csr-id-22e71e59be566136f6028393153827662ec9f68e/> import `wrpc-runtime-wasmtime`
 - <csr-id-6678fead03a5d4ea893b74863b0fe043ff81a3d1/> remove `wit-component` dep
   Ciao
 - <csr-id-9dc14c54eb133c08dace6e6a6f96f915f0fcda6f/> appease Clippy
   Chillax, Clip
 - <csr-id-eee6c73122b715d6991bb6c76f04d29fc9319fe0/> switch wasi-keyvalue to `main`
 - <csr-id-089b8955d309b1cab3eaa45f03d394656deada55/> fix `wasi-keyvalue` incoming value ownership mismatch
 - <csr-id-08b8a3c72902e6d8ff4f9dcaa95b9649f3716e75/> implement preview 2 interfaces
 - <csr-id-a7e0e130343f5a3ca4874035016c9b5a181a917a/> update WIT packages
 - <csr-id-8b7152a5a702d56f70930302b5fe6e7b76858979/> remove logging `with` pin
 - <csr-id-7a6e6a0dc69720ed4b52a476539970811f5bac72/> update to Wasmtime 15
 - <csr-id-2389f27f0b570164a895a37abd462be2d68f20be/> polish tracing and logging levels
 - <csr-id-dfad0be609868cbd0f0ce97d7d9238b41996b5fc/> integrate `wash` into the workspace
 - <csr-id-831e90192f258dff1060c7ac8bd9425009ab8335/> update to Wasmtime 14 and latest WIT
 - <csr-id-93c0981a4d69bc8f8fe06e6139e78e7f700a3115/> resolve 1.73.0 warnings
 - <csr-id-0023f7e86d5a40a534f623b7220743f27871549e/> reduce verbosity of instrumented functions
 - <csr-id-099ebcd9855b13b810f8fbb11ac57816e9dd4c06/> mark non-exhaustive Debug impls as such
 - <csr-id-4fb8206e1d5fb21892a01b9e4f009e48c8bea2df/> remove noisy fields from instruments

### New Features

<csr-id-cfb66f81180a3b47d6e7df1a444a1ec945115b15/>
<csr-id-2e8982c962f1cbb15a7a0e34c5a7756e02bb56a3/>
<csr-id-123cb2f9b8981c37bc333fece71c009ce875e30f/>
<csr-id-813ce52a9c11270814eec051dfaa8817bf9f567d/>
<csr-id-bef159ab4d5ce6ba73e7c3465110c2990da64eac/>
<csr-id-d434e148620d394856246ac34bb0a64c37181970/>
<csr-id-50d0ed1086c5f417ed64dcce139cc3c2b50ca14c/>
<csr-id-54f0afa7b7d67b658113eb2a7ea667b77ea4bd55/>
<csr-id-2e3bd2bd7611e5de9fe123f53778f282613eb0de/>
<csr-id-77d663d3e1fd5590177ac8003a313a3edf29ab1f/>
<csr-id-02c1ddc0d62b40f63afe4d270643ebc3bf39c081/>
<csr-id-9eda090fe6d790f239093738515570a7886eae8d/>
<csr-id-4de853a1d3e28126faf9efa51aaa97714af7b493/>
<csr-id-3ae7cce621b4be163feac7be903f3ff66f40ddc3/>
<csr-id-e943eca7512a0d96a617451e2e2af78718d0f685/>
<csr-id-7364dd8afae5c8884ca923b39c5680c60d8d0e3d/>

 - <csr-id-056b57e50cfc13ecd863f54d30032988bd23d94b/> enable wasmtime gc feature
 - <csr-id-26d7f64659dbf3263f36da92df89003c579077cc/> fallback to `wrpc:blobstore@0.1.0`
 - <csr-id-156d3f39e6775ec6aea3a1eb864bf7c893749e07/> update to Wasmtime 23
 - <csr-id-070751231e5bb4891b995e992e5206b3050ecc30/> pass original component instance through the context
 - <csr-id-9cb1b784fe7a8892d73bdb40d1172b1879fcd932/> upgrade `wrpc`, `async-nats`, `wasmtime`
 - <csr-id-a5f9432845bcb7c8f423776fd56ef4a735fe43c7/> add `TargetEntity::lattice_id()`
 - <csr-id-077a28a6567a436c99368c7eb1bd5dd2a6bc6103/> gracefully shutdown epoch interrupt thread
 - <csr-id-f986e39450676dc598b92f13cb6e52b9c3200c0b/> generate crate changelogs
 - <csr-id-3eb453405aa144599f43bbaf56197566c9f0cf0a/> count epoch in a separate OS thread
 - <csr-id-a66921edd9be3202d1296a165c34faf597b1dec1/> propagate `max_execution_time` to the runtime
 - <csr-id-e928020fd774abcc213fec560d89f128464da319/> limit max execution time to 10 minutes
 - <csr-id-33b50c2d258ca9744ed65b153a6580f893172e0c/> update to Wasmtime 20
 - <csr-id-9cd2b4034f8d5688ce250429dc14120eaf61b483/> update `wrpc:keyvalue` in providers
   part of this process is adopting `wit-bindgen-wrpc` in the host
 - <csr-id-a1754195fca5a13c8cdde713dad3e1a9765adaf5/> update `wasi:keyvalue`
 - <csr-id-2352092930b50992e47e7fcf013ae5f084bf2a8e/> Bumps our wasmcloud wit to 1.0
   This bumps our main `wasmcloud:bus` package and the package in the `runtime`
   crate to 1.0.0 in preparation for release. Also removes the use of
   the wasmcloud interface in tests where it wasn't needed
 - <csr-id-023358b41b154e75a737f10f652e197dfa6b0093/> update to wasmtime 19
 - <csr-id-f56492ac6b5e6f1274a1f11b061c42cace372122/> migrate to `wrpc:keyvalue`
 - <csr-id-383b3f3067dddc913d5a0c052f7bbb9c47fe8663/> implement `wrpc:blobstore/blobstore` for FS
 - <csr-id-614af7e3ed734c56b27cd1d2aacb0789a85e8b81/> implement Redis `wrpc:keyvalue/{atomic,eventual}`
 - <csr-id-e0dac9de4d3a74424e3138971753db9da143db5a/> implement `wasi:http/outgoing-handler` provider
 - <csr-id-0c5aee7621f01f6a3a90322c55836f45184df79a/> support p1 module execution
 - <csr-id-76c1ed7b5c49152aabd83d27f0b8955d7f874864/> support pubsub on wRPC subjects
   Up until now, publishing and subscribing for RPC communcations on the
   NATS cluster happened on subjects that were related to the wasmbus
   protocol (i.e. 'wasmbus.rpc.*').
   
   To support the WIT-native invocations, i.e. wRPC (#1389), we must
   change the publication and subscription subjects to include also the
   subjects that are expected to be used by wprc.
   
   This commit updates the provider-sdk to listen *additionally* to
   subjects that are required/used by wrpc, though we do not yet have an
   implementation for encode/deocde.
 - <csr-id-590a49477d5832ec99f3b2e251813d51b4abb274/> Switches runtime config to use a pooling allocator
   This leads to significant performance increases on Linux and brings it
   up to the same performance levels as other operating systems
 - <csr-id-400802ac767a06459fc1d93c3ab5cd4223e8506f/> improve byte stream efficiency
 - <csr-id-25e3e51d7e123aae3e3681886d2e095b29202b94/> Switches modules to use pre instantiation instead
   In my load testing of this locally, this led to a 20% increase in throughput
 - <csr-id-f2223a3f5378c3cebfec96b5322df619fcecc556/> implement `wrpc:http/incoming-handler`
 - <csr-id-0c0c004bafb60323018fc1c86cb13493f72d29cd/> switch to `wrpc` for `wasmcloud:messaging`
 - <csr-id-5ede01b1fe0bc62234d2b7d6c72775d9e248a130/> switch to `wrpc:{keyvalue,blobstore}`
 - <csr-id-246384524cfe65ce6742558425b885247b461c5c/> implement `wrpc:http/outgoing-handler.handle`
 - <csr-id-5d19ba16a98dca9439628e8449309ccaa763ab10/> change set-target to set-link-name
   Up until the relatively low-level `wasmcloud:bus/lattice` WIT
   interface has used a function called `set-target` to aim invocations
   that occurred in compliant actors and providers.
   
   Since wRPC (#1389)
   enabled  wasmCloud 1.0 is going to be WIT-first going forward, all
   WIT-driven function executions have access to the relevant
   interface (WIT interfaces, rather than Smithy-derived ones) that they
   call, at call time.
   
   Given that actor & provider side function executions have access to
   their WIT interfaces (ex. `wasi:keyvalue/readwrite.get`), what we need
   to do is differentiate between the case where *multiple targets*
   might be responding to the same WIT interface-backed invocations.
   
   Unlike before, `set-target` only needs to really differentiate between *link
   names*.
   
   This commit updates `set-target` to perform differentiate between link
   names, building on the work already done to introduce more opaque
   targeting via Component IDs.
 - <csr-id-5d1590e231f75e4d418a5115b3449dda0dadec9a/> record polyfilled component imports
 - <csr-id-18875a7264ec4b8c0a82f3389be72267be202e58/> fix custom interface support and tests
 - <csr-id-fec6f5f1372a1de5737f5ec585ad735e14c20480/> remove module support
 - <csr-id-219342386861f21fab64429cad4f8e88ae679c0a/> add resource handling stubs
 - <csr-id-eb61ce2f38d788ae2ebd286a5d4511c7a4a8c57a/> support composite types
 - <csr-id-da6e2b3a91013c8564c22f8305d665aec78a072d/> support composite Wasmtime type reflection in polyfills
 - <csr-id-713e7746a9aa61ceff373cf62cf85e68617fa788/> add (most of) custom interface plumbing
 - <csr-id-64d21b1f3d413e4c5da78d8045c1366c3782a190/> Adds some additional context around test failures I was seeing
 - <csr-id-1a048a71320dbbf58f331e7e958f4b1cd5ed4537/> Adds support for actor config
   This is a fairly large PR because it is adding several new control interface
   topics as well as actually adding the actor config feature.
   
   This feature was motivated by 2 major reasons:
   
   1. We have been needing something like this for a while, at the very least for
   being able to configure link names in an actor at runtime
2. There aren't currently any active (yes there were some in the past) efforts
      to add a generic `wasi:cloud/guest-config` interface that can allow any host
      to provide config values to a component. I want to use this as a springboard
      for the conversation in wasi-cloud as we will start to use it and can give
      active feedback as to how the interface should be shaped
- make claims optional (at least for now)
- add streaming support to `wasmcloud:bus`
- rename `wasmcloud_host` -> `wasmcloud_runtime`
- remove all `wasmcloud-interface-*` usages
- add support for `command` executables (I/O actors)
- add local lattice proving the concept, which is used for testing of the feature
- implement an actor instance pool

### Bug Fixes

<csr-id-fa1fde185b47b055e511f6f2dee095e269db1651/>
<csr-id-61308b7827789d442b2508ba5347add03bdbb069/>
<csr-id-7abc17038655db16e71471edd2cc7dc0a760b6ac/>
<csr-id-4ed38913f19fcd4dd44dfdcc9007e80e80cdc960/>
<csr-id-ccb3c73dc1351b11233896abc068a200374df079/>
<csr-id-bff9816db3193c57ccfe48852f21258a8430530e/>
<csr-id-c8f26b84346600870f62df05238f64421c6e66c6/>
<csr-id-149f98b60c1e70d0e68153add3e30b8fb4483e11/>
<csr-id-0f6a1eb97cb46a43c9b24977a8e8dc11061af330/>
<csr-id-d1c3a599377ccb46ba11f2d9484812dc2a67b22c/>
<csr-id-923c650cc4b58e5316e53ae8141219de15862d34/>
<csr-id-e9bea42ed6189d903ea7fc6b7d4dc54a6fe88a12/>
<csr-id-542427e4a0bff82c25ffe35c9587f34783a207dd/>
<csr-id-c6fa704f001a394c10f8769d670941aff62d6414/>
<csr-id-7db1183dbe84aeeb1967eb28d71876f6f175c2c2/>
<csr-id-1d3fd96f2fe23c71b2ef70bb5199db8009c56154/>
<csr-id-c555bab75cdc6f2953ec394b4fe41133d83efb66/>
<csr-id-1829b27213e836cb347a542e9cdc771c74427892/>
<csr-id-b13a50ca8b882fe5142f9ad26501ffeba47af24c/>
<csr-id-a82847f4e4a2637bc9d6f9c75be0a902f7944212/>

 - <csr-id-b014263cf3614995f597336bb40e51ab72bfa1c9/> setup debug traces
   This commit contains experimental code used to debug/replicate the
   o11y traces for making a call with http-client & http-provider.
   
   Running this requires the following hackery:
   
   - running the docker compose for o11y

### Other

 - <csr-id-7cd2e71cb82c1e1b75d0c89bd5bda343016e75f4/> bump for test-util release
   Bump wasmcloud-core v0.8.0, opentelemetry-nats v0.1.1, provider-archive v0.12.0, wasmcloud-runtime v0.3.0, wasmcloud-secrets-types v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, safety bump 8 crates
   
   SAFETY BUMP: wasmcloud-runtime v0.3.0, wasmcloud-secrets-client v0.3.0, wasmcloud-tracing v0.6.0, wasmcloud-host v0.82.0, wasmcloud-test-util v0.12.0, wasmcloud-provider-sdk v0.7.0, wash-cli v0.30.0, wash-lib v0.23.0
 - <csr-id-78b9bc7b9dbb7e1bb3ffc6896f01f8e030f3c5b1/> improve documentation
 - <csr-id-663b49e335d2645d0cfd679afd202ca461dd6932/> clarify the instance exclusions
 - <csr-id-03c9d1c6ae662d3018ebc9d4d8c509076e291f12/> update to Wasmtime 18
 - <csr-id-49f3883c586c098d4b0be44793057b97566ec2e1/> update to wasmtime 17
 - <csr-id-75c0739a4db4264996a7fa87ce3ae39f56780759/> update to wasmtime 16
   Note this uses a release branch as 16 is not out yet.
 - <csr-id-a278764abaac2b745b833aaea8e041e357b97a15/> pin blobstore to upstream rev
   Pin until https://github.com/WebAssembly/wasi-blob-store/pull/14 merged
 - <csr-id-d16324054a454347044f7cc052da1bbd4324a284/> bump crate versions
 - <csr-id-578c72d3333f1b9c343437946114c3cd6a0eead4/> bump to `0.79.0`
 - <csr-id-22276ff61bcb4992b557f7af6624c9715f72c32b/> update dependencies
 - <csr-id-31799820202aa3556f6ad84ca5550402e6da0fef/> switch to upstream `wasi:blobstore`
 - <csr-id-083f8e833889a49d09a4dafa1998a58f7380562a/> update WIT dependencies
 - <csr-id-1f3448e6b38ffdad064d79145470ca1a7a476508/> update to Wasmtime 12
 - <csr-id-2bb60f364ef573e5837c5299eb587ec4e1427d3f/> update WIT dependencies
   This fixes `poll-oneof` mismatch
 - <csr-id-cb86378831e48368d31947b0a44ef39080fe6d70/> update dependencies

### Refactor

 - <csr-id-3fb79daf65f9f029ca0227cfdac7b504d7bd9c6c/> use upstream preview1 adapter crate
 - <csr-id-9463be2cc3dcaf2e272e5372800e65378c16217f/> extract and document `InvocationStream` type
 - <csr-id-468268e015ccc5d5d8a607dcf3ede7c5e86de45e/> wascap::jwt::Actor -> wascap::jwt::Component
 - <csr-id-e1281733c73988686a499d43e808e4cd11fd5759/> link actors on creation
 - <csr-id-770731ca949c5906ccbd102bcf13dc57a870f7b7/> improve WASI linking error
 - <csr-id-017e6d40841f14b2158cf2ff70ca2ac8940e4b84/> remove instance pooling
 - <csr-id-6c42d5c50375cdc2d12c86513a98b45135f0d187/> reduce verbosity on actor logs
 - <csr-id-b5aac8ea84af9cc37282b99826b2da0c0ec297bc/> component instantiation error message
 - <csr-id-2540b2a2776c8977e47232993b2af5086dc92e18/> split interface implementations into separate modules

### Test

 - <csr-id-5f922256e679091e6acbb3e0f39852abb840c8b0/> replicate component test in modules and compat

### New Features (BREAKING)

 - <csr-id-fc1bbf45e212b2d00b654a27a38a7322e8889be6/> increase wasm memory limit, 256MiB
 - <csr-id-2c0b5860390373720845cc2060705ad7d942a3c3/> implement streaming in wasi:blobstore
 - <csr-id-f4b4eeb64a6eab4f6dfb540eacd7e2256d80aa71/> allow tuning runtime parameters
 - <csr-id-acb6e9c3a4c0bf3f10d81dabbda347114bd62cf5/> add secrets store/reveal imports
 - <csr-id-6b2e1b5915a0e894a567622ffc193230e5654c1f/> Removes old guest config and uses runtime config instead
   Most of the changes are related to wit updates, but this removes the
   guest config from `wasmcloud:bus` and pulls down `wasi:config` in its
   place
 - <csr-id-91874e9f4bf2b37b895a4654250203144e12815c/> convert to `wrpc:blobstore`
 - <csr-id-716d251478cf174085f6ff274854ddebd9e0d772/> use `wasmcloud:messaging` in providers
   Also implement statically invoking the `handler` on components in the
   host
 - <csr-id-5af1138da6afa3ca6424d4ff10aa49211952c898/> support interface link put, component spec
 - <csr-id-42d069eee87d1b5befff1a95b49973064f1a1d1b/> Updates topics to the new standard
   This is a wide ranging PR that changes all the topics as described
   in #1108. This also involved removing the start and stop actor
   operations. While I was in different parts of the code I did some small
   "campfire rule" cleanups mostly of clippy lints and removal of
   clippy pedant mode.

<csr-unknown>
<csr-unknown>
<csr-unknown>
(re) building dog-fetchermodifying the WADM w/ dog fetcher (done by this commit)build & create PAR for http-clientbuild & create PAR for http-serverset WASMCLOUD_OVERRIDE_TRACES_ENDPOINT before wash upreplacing existing wasmcloud host (in ~/.wash/downloads/v1.0.2)Adds missing implementation to bindgen for provider -> actor invocationsUncomments implementation from the host for wasmcloud:messagingAdds an invoker component that reacts to messaging rather than HTTPUses messaging & keyvalue providers plus the actor in a single test<csr-unknown>
With that said, note that this is only going to be added for actors built againstthe component model. Since this is net new functionality, I didn’t think it wasworth it to try to backport.As for testing, I have tested that an actor can import the functions and get the valuesvia the various e2e tests and also manually validated that all of the new topicswork. implement wasifills for simple types implement outgoing HTTP add support for call aliases support chunking and dechunking of requests implement wasi:blobstore partially implement wasi:keyvalue/atomic implement wasmcloud:http/incoming-handler support move builtin smithy structs to compat implement link names and a2a calls implement wasmcloud:messaging/consumer support implement wasi:keyvalue/readwrite support introduce Blobstore trait implement actor -> provider linking provide wasmCloud interface stubs implement linkdef add/delete implement data streaming propagate traces through components Fixes issue with running runtime on smaller hostsWe found that on hosts with less then 2GB of memory (give or take alittle) the host would fail to start when the pooling allocator startedallocating virtual memory. You could get around this by settingvm_overcommit to 1 or 2, but this is not the best experience for thoserunning in production. This fixes the issue by falling back to thedynamic memory allocator if setup fails.We already have a plan to add some more of these tunables as optionsfor the host, but those will be added in future PRs as a feature add rustdoc spelling fix link_name functionality, reorganize tests correct name and data streaming, update WIT do not polyfill wasi:blobstore interfaces do not polyfill wasi cloud interfaces improve target lookup error handling add messaging triggered test actorThis commit is the culmination of a few things that were required forgetting our flavor of E2E tests (in the top level tests/ dir)working for a Provider & Actor.This commit is quite large because it does many things:With this, we have an easy to understand way to test every providerthat we have in the repository. do not polyfill logging tone down instrumentation level bindgen issues preventing buildsThis commit fixes the provider bindgen issues for non http-serverbuilds (ex. kv-redis) parse package fix clippy warning, added ; for consistency, return directly the instance instead of wrapping the instance’s components in a future Add comments, remove useless future::ready fmt return Ready on trailers allow namespaces with slashes properly handle path_with_query switch to wasmCloud messaging WIT<csr-unknown/>
<csr-unknown/>
<csr-unknown/>
<csr-unknown/>

