# PReSto Temp12k baseline: Temperature 12k v1.0.0, pickle path

The comparison run for
[presto-Temp12k-run-2026-10-08](https://github.com/paleopresto/presto-Temp12k-run-2026-10-08):
the same code and config, the same data pathway (`mode: bundle`, single
value series with the emulator's banded age model), run on Kaufman et al.
(2020)'s records ([baseline-temp12k-1_0_0](https://github.com/paleopresto/presto-recipes/releases/tag/baseline-temp12k-1_0_0)).

The emulator's validated replication uses the real age/value ensembles
instead (`PRESTO_REALENS=1`), which new pool records do not have; comparing
the pool run against that would mix a change of method into the change of
data.
