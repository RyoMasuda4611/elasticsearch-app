# Ruby on Rails and Elasticsearch: Example application

* The Elasticsearch integration is refactored into the `Searchable` concern
* A complex mapping for the index is defined
* A custom serialization is defined in `Article#as_indexed_json`
* The `search` method is amended with facets and suggestions
* A [Sidekiq](http://sidekiq.org) worker for handling index updates in background is added
* A custom `SearchController` with associated view is added
* A Rails initializer is added to customize the Elasticsearch client configuration
* Seed script and example data from New York Times is added

