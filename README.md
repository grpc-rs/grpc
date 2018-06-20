<!---
    Copyright 2018 quic-rs
 
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
 
        http://www.apache.org/licenses/LICENSE-2.0
 
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->

# Another rust-lang [gRPC][] implemention

## Why

I think [Actor Concurrency Model][actor] will be another good choose for [Distributed Systems][distributed computing]. And the [gRPC][] network framework has became more and more popular. So let's keep an eye on the combination of both, maybe it will be interesting!

## Inspired

- [gRPC][] an open-source rpc framework contributed by Google.
- [tower-grpc][] A [gRPC][] implemention with rust-lang. 
- [actix][] A fast actor framework for rust-lang.





[tower-grpc]: https://github.com/tower-rs/tower-grpc
[actix]: https://github.com/actix
[gRPC]: https://grpc.io/
[actor]: https://en.wikipedia.org/wiki/Actor_model
[distributed computing]: https://en.wikipedia.org/wiki/Distributed_computing