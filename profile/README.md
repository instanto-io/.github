# instanto.io

**Portable Java, tailored for the JVM, JavaScript, WebAssembly, and edge** — powered by [TeaVM](https://teavm.org/).

Write Java once with compile-time, reflection-free code generation and deploy across JVM servers, desktop hosts, browser JavaScript and WebAssembly, Web Workers, and Cloudflare Workers.

<table>
  <tr>
    <td width="50%" valign="top">
      <p>
        <a href="https://sarto.instanto.io">
          <img src="https://raw.githubusercontent.com/instanto-io/.github/main/profile/assets/sarto-mark.svg" width="52" height="52" alt="Sarto" align="left" style="margin-right: 14px;" />
        </a>
        <strong><a href="https://sarto.instanto.io">Sarto</a></strong><br />
        <em>Portable Java libraries &amp; distributed computing framework</em>
      </p>
      <p>
        Two complementary layers: standalone, portable Java <strong>libraries</strong> for any JVM or TeaVM codebase (compile-time CDI, codecs, async, signals, REST/SOAP/gRPC, persistence, Cloudflare Workers, 2D graphics &amp; scene graph) — plus the <strong>Sarto Framework</strong> for distributed computing across JVM, browser, worker, and edge topologies.
      </p>
      <p>
        <a href="https://sarto.instanto.io">Site &amp; Docs</a> ·
        <a href="https://github.com/instanto-io/sarto-framework">sarto-framework</a> ·
        <a href="https://github.com/instanto-io/sarto-scene">sarto-scene</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <p>
        <a href="https://verrai.dev">
          <img src="https://raw.githubusercontent.com/instanto-io/.github/main/profile/assets/verrai-mark.svg" width="52" height="52" alt="Verrai" align="left" style="margin-right: 14px;" />
        </a>
        <strong><a href="https://verrai.dev">Verrai</a></strong><br />
        <em>HTML-first Java web applications for the browser</em>
      </p>
      <p>
        Type-safe browser UIs in the spirit of Errai — ordinary HTML templates, compile-time CDI, two-way data binding, and typed navigation built on Sarto libraries, free to connect to Spring Boot, Quarkus, Jakarta EE, or Sarto backends.
      </p>
      <p>
        <a href="https://verrai.dev">Site</a> ·
        <a href="https://github.com/instanto-io/verrai">verrai</a>
      </p>
    </td>
  </tr>
</table>

## Libraries vs. Distributed Framework

All artifacts publish under `io.instanto` with `sarto-*` and `verrai-*` prefixes. Every standalone Sarto library is independently usable without adopting `sarto-framework`.

| Category | What it provides | Repositories |
| --- | --- | --- |
| **Sarto Portable Libraries** | Standalone JVM &amp; TeaVM libraries — adopt individually with no framework lock-in | [`sarto-async`](https://github.com/instanto-io/sarto-async) · [`sarto-cdi`](https://github.com/instanto-io/sarto-cdi) · [`sarto-codec`](https://github.com/instanto-io/sarto-codec) · [`sarto-signals`](https://github.com/instanto-io/sarto-signals) · [`sarto-events`](https://github.com/instanto-io/sarto-events) · [`sarto-config`](https://github.com/instanto-io/sarto-config) · [`sarto-resources`](https://github.com/instanto-io/sarto-resources) · [`sarto-invoke`](https://github.com/instanto-io/sarto-invoke) · [`sarto-rest`](https://github.com/instanto-io/sarto-rest) · [`sarto-soap`](https://github.com/instanto-io/sarto-soap) · [`sarto-grpc`](https://github.com/instanto-io/sarto-grpc) · [`sarto-auth`](https://github.com/instanto-io/sarto-auth) · [`sarto-model`](https://github.com/instanto-io/sarto-model) · [`sarto-persistence`](https://github.com/instanto-io/sarto-persistence) · [`sarto-edge`](https://github.com/instanto-io/sarto-edge) |
| **Sarto Distributed Framework** | Full-stack distributed computing: typed `@Service` contracts, RPC, pub/sub, relays, REST/SOAP interop, and JVM/browser/edge host runtimes | [`sarto-framework`](https://github.com/instanto-io/sarto-framework) · [`sarto-relay`](https://github.com/instanto-io/sarto-relay) |
| **Browser UI &amp; Retained Graphics** | HTML-first web apps (`Verrai`) and portable 2D canvas/desktop scene graphs (`Sarto Scene` &amp; `Graphics`) | [`verrai`](https://github.com/instanto-io/verrai) · [`sarto-scene`](https://github.com/instanto-io/sarto-scene) · [`sarto-graphics`](https://github.com/instanto-io/sarto-graphics) · [`sarto-geo`](https://github.com/instanto-io/sarto-geo) |

---

*Built on [TeaVM](https://github.com/konsoletyper/teavm) · Apache License 2.0 · [Sponsor Instanto](https://github.com/sponsors/instanto-io)*
