# WeightLoss

Single static Astro page charting actual weight measurements against a straight
target line.

- `src/data/target.yml` — start and end of the target line (80 kg on 1 Oct → 70 kg on 1 Mar).
- `src/data/measured.yml` — actual measurements, one `date` / `weight` pair per entry.

```sh
npm install
npm run dev
npm run build
```
