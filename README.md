# Canary Islands — an XPlatform catalog

Eighteen paved roads worth riding on six of the seven islands: the Teide and
the Masca road on Tenerife, the Cumbre of Gran Canaria, the Roque de los
Muchachos on La Palma, and the coast and ridge roads of La Gomera, Lanzarote
and Fuerteventura.

## Add it to XPlatform

1. Open **Catalogs**, then **Add**.
2. Type `tillda/xplatform-catalog-canary-islands` and confirm.

The catalog installs as `user/canary-islands`. **Check for updates** compares
its `version` with this repository's `index.yaml` and offers the newer one.

## Files

| File | Holds |
| --- | --- |
| `index.yaml` | the catalog's `id`, `version`, name and file list |
| `canary-islands-paved.map.md` | the roads, one Entry each |

## Sources and licence

- Roads come from web research held to the XPlatform destination library's
  evidence bar: three independent sites name each road.
- The descriptions are original text.

## Releasing a new version

Edit the files, raise `version` in `index.yaml` (dotted numbers: `1`, `1.1`,
`2`), and push. The app refuses an update whose `id` differs.
