# gitnedict

Git-friendly JSON representation of [JMnedict](https://www.edrdg.org/enamdict/enamdict_doc.html), generated
by [SumatoraIndex](https://github.com/HappyPeng2x/SumatoraIndex)'s `jmnedict-to-git.py`. One JSON file per
named entity (`entries/<shard>/<seq>.json`), sharded by `seq // 10000`.

This repository is regenerated and pushed automatically by SumatoraIndex's monthly release workflow.
Manual edits here will be overwritten on the next sync.

## License

JMnedict is the property of James William Breen and the
[Electronic Dictionary Research and Development Group](https://www.edrdg.org/), distributed under
[Creative Commons Attribution-ShareAlike 4.0 International](LICENSE) (CC BY-SA 4.0), per the Group's
[licence terms](https://www.edrdg.org/edrdg/licence.html). This repository, as a derivative work, is
licensed under the same terms.
