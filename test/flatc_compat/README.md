Basic sanity check to verify that a `flatcc` generated reader can read
binaries generated by Googles `flatc` compiler.

`monsterdata_test.mon` is generated by Googles flatc compiler using the
`monsterdata_test.golden` json as input and `monster_test.fbs` as schema.

`monsterdata_test.json` was also copied for completeness - it apparently
relates to undocumented hash attributed that converts json strings into
hashes where the golden file has the correct target type with respect to
the schema..
