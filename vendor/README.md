# Vendored LAIX

Pinned LAIX TypeScript package used by the RECALL web app.

- **Tag:** `v0.6.0`
- **Package:** `laix@0.6.0`
- **Source:** `C:\Workspace\laix\packages\typescript\laix` (read-only for RECALL)
- **Packed with:**

```powershell
cd C:\Workspace\laix\packages\typescript\laix
npm pack --pack-destination C:\Workspace\openjiuwendemos\recall\vendor
```

- **Tarball:** `laix-0.6.0.tgz`
- **SHA-256:**

```
E38A039F887A442FE573A5C04E4A204E1DBD1323958706204EA31C33CD527760
```

The package ships its own `types.d.ts`; the web app no longer keeps a local
TypeScript declaration bridge.

Do not edit the tarball. To upgrade, pack the new tag, update `web/package.json`
and record the new SHA-256 here.
