# NetWitness Suite Log Parsers Repository

A repository to share and contribute event source log parsers for the NetWitness Log Decoder.

A log parser defines how a NetWitness Log Decoder identifies, parses, and extracts information from the events of a specific event source. These parser definitions are stored as an XML file, called an event source XML file, which is deployed on the NetWitness platform.

You can create a new event source parser for an event source that is not currently supported by NetWitness and share it with the NetWitness community. You can also edit an existing event source parser to add or edit definitions for events, or to correct errors. You may need to edit an event source parser in one of the following situations:

- You upgrade to a new version of an event source that contains new, updated, or deprecated
event messages.
- You want to include additional definitions for existing events.
- You want to update the definition for an existing event in an event source parser.
- You want to correct errors in an event source parser.

GitHub members can contribute to the repository by adding/editing an event source parser by raising a Pull Request and it'll be reviewed by our engineers for final check.

Please read LogParser101 document to understand the guidelines on log parser development and best practices.

Please go through below guide to understand the GitHub workflow to be followed: https://guides.github.com/introduction/flow/

More information related to GitHub can be found here: https://services.github.com/on-demand/intro-to-github/

Note: Any new event source parser which is not yet supported by RSA should be added under community directory, list of all supported event sources are available here: https://community.rsa.com/community/products/netwitness/parser-network/event-sources and all supported latest log parsers are available under devices directory.
