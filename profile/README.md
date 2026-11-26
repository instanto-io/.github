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
        <em>Portable Java libraries, distributed framework &amp; retained graphics</em>
      </p>
      <p>
        Standalone JVM &amp; TeaVM building blocks (compile-time CDI, codecs, async, signals, REST/SOAP/gRPC, persistence, Cloudflare Workers), a full-stack distributed service framework, and a portable 2D scene graph.
      </p>
      <p>
        <a href="https://sarto.instanto.io">Docs</a> ·
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
        Type-safe browser UIs in the spirit of Errai — ordinary HTML templates, compile-time CDI, two-way binding, and typed navigation built on Sarto bricks, free to connect to Spring Boot, Quarkus, Jakarta EE, or Sarto backends.
      </p>
      <p>
        <a href="https://verrai.dev">Site</a> ·
        <a href="https://github.com/instanto-io/verrai">verrai</a>
      </p>
    </td>
  </tr>
</table>

## Core Building Blocks

All libraries publish under `io.instanto` with `sarto-*` and `verrai-*` artifact prefixes, and each standalone brick can be adopted independently of `sarto-framework`:

| Layer | Repositories |
| --- | --- |
| **Portable Core** | [`sarto-async`](https://github.com/instanto-io/sarto-async) · [`sarto-cdi`](https://github.com/instanto-io/sarto-cdi) · [`sarto-codec`](https://github.com/instanto-io/sarto-codec) · [`sarto-signals`](https://github.com/instanto-io/sarto-signals) · [`sarto-events`](https://github.com/instanto-io/sarto-events) · [`sarto-config`](https://github.com/instanto-io/sarto-config) · [`sarto-resources`](https://github.com/instanto-io/sarto-resources) · [`sarto-invoke`](https://github.com/instanto-io/sarto-invoke) |
| **Services & Interop** | [`sarto-framework`](https://github.com/instanto-io/sarto-framework) · [`sarto-rest`](https://github.com/instanto-io/sarto-rest) · [`sarto-soap`](https://github.com/instanto-io/sarto-soap) · [`sarto-grpc`](https://github.com/instanto-io/sarto-grpc) · [`sarto-auth`](https://github.com/instanto-io/sarto-auth) · [`sarto-model`](https://github.com/instanto-io/sarto-model) · [`sarto-persistence`](https://github.com/instanto-io/sarto-persistence) · [`sarto-edge`](https://github.com/instanto-io/sarto-edge) |
| **UI & Graphics** | [`verrai`](https://github.com/instanto-io/verrai) · [`sarto-scene`](https://github.com/instanto-io/sarto-scene) · [`sarto-graphics`](https://github.com/instanto-io/sarto-graphics) · [`sarto-geo`](https://github.com/instanto-io/sarto-geo) |

---

*Built on [TeaVM](https://github.com/konsoletyper/teavm) · Apache License 2.0 · [Sponsor Instanto](https://github.com/sponsors/instanto-io)*
