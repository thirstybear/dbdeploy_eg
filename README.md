# Simple DBDeploy example 

 * Uses Ant script
 * Uses MySQL 5.x
 * Designed to allow people to look at what DBDeploy does internally to the database

### Basics
 * Start with a basic schema and use scripts to add to it.
 * Test data is separate from deployment data.

### Targets
`resetDB` - nuke the entire database and start again from scratch

`bringDbUpToDate` - update database to latest version, preserving data

`populateTestData` - populates database with test data. Runs `bringDbUpToDate` first 