# Persistence

SQLite persistence is planned but not yet implemented. Schema changes will use
explicit, numbered, transactional migrations. Public identity will use UUIDs,
never SQLite row IDs. Foreign keys will be enabled for every connection.

