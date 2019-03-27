Consul-Git-Sync
========
`Consul-Git-Sync` is a java based tool helping to synchronize [consul](https://www.consul.io/) with properties from git repository.
Still under development phase!      

## Future features to be added:
* Command line tool capable of featching properties from git and updateing consul key value store
* Polling confiruation
* Simple and lightweight ttp server allowing online access to configuration and synchronization on demand. 
* Rest endpoint for git webhooks, allowing synchronization only when changes occured in repo.

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details

## Dependencies and Acknowledgments

* [JGit](https://www.eclipse.org/jgit/)
* [Consul api java client](https://github.com/Ecwid/consul-api)
