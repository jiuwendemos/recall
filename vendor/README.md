# Vendored LAIX

Pinned LAIX TypeScript package used by the RECALL web app.

- **Tag:** `v0.3.2`
- **Package:** `laix@0.3.2`
- **Source:** `C:\Workspace\laix\typescript\laix` (read-only for RECALL)
- **Packed with:**

```powershell
cd C:\Workspace\laix\typescript\laix
npm pack --pack-destination C:\Workspace\openjiuwendemos\recall\vendor
```

- **Tarball:** `laix-0.3.2.tgz`
- **SHA-256:**

```
588321C3B8F5CE988DAABE6B5D2542DCE24195C6BC3DDB1D10D5177D1CDB0888
```

The package ships its own `types.d.ts`; the web app no longer keeps a local
TypeScript declaration bridge.

Do not edit the tarball. To upgrade, pack the new tag, update `web/package.json`
and record the new SHA-256 here.
