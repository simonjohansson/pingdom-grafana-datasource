## Setup

```bash
$ git clone https://github.com/simonjohansson/pingdom-grafana-datasource.git; cd pingdom-grafana-datasource
$ yarn install
$ npm run build

# Follow http://docs.grafana.org/project/building_from_source/ , build and start the server.
$ ln -s $PWD/dist $GOPATH/src/github.com/grafana/grafana/data/plugins/pingdom-grafana-datasource


# Any time you make a change to the plugin simply
$ npm run build
# No need to restart grafana
```
