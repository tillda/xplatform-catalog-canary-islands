# Canary Islands — an XPlatform catalog

Twenty-two paved roads worth riding on all seven islands: the Teide, the
Masca road and the Anaga on Tenerife, the Cumbre and the west coast road of
Gran Canaria, the Roque de los Muchachos on La Palma, the road to the Orchilla
lighthouse on El Hierro, Timanfaya on Lanzarote, and the coast and ridge roads
of La Gomera and Fuerteventura.

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
