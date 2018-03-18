# [The base for IRIS Knowledge Platform](forum.team-iris.me)
This is our submission for the Coding Culture Hackathon.<br>
We built the forum using discourse. The instructions to install are here. 

### [Round 1 submission file](https://github.com/Nikhil-Kasukurthi/discourse/raw/master/forum.pdf)

## Development
<a href="http://www.discourse.org/">![Logo](images/discourse.png)</a>

Discourse is the 100% open source discussion platform built for the next decade of the Internet. 

1. If you're **brand new to Ruby and Rails**, please see [**Discourse as Your First Rails App**](http://blog.discourse.org/2013/04/discourse-as-your-first-rails-app/) or our [**Discourse Vagrant Developer Guide**](docs/VAGRANT.md), which includes a development environment in a virtual machine.

2. If you're familiar with how Rails works and are comfortable setting up your own environment, use our [**Discourse Advanced Developer Guide**](docs/DEVELOPER-ADVANCED.md).

Before you get started, ensure you have the following minimum versions: [Ruby 2.3+](http://www.ruby-lang.org/en/downloads/), [PostgreSQL 9.3+](http://www.postgresql.org/download/), [Redis 2.6+](http://redis.io/download). If you're having trouble, please see our [**TROUBLESHOOTING GUIDE**](docs/TROUBLESHOOTING.md) first!

## Setting up Discourse

If you want to set up a Discourse forum for production use, see our [**Discourse Install Guide**](docs/INSTALL.md).

If you're looking for business class hosting, see [discourse.org/buy](https://www.discourse.org/buy/).

## Requirements

Discourse is built for the *next* 10 years of the Internet, so our requirements are high:

| Browsers | Tablets |  Phones |
| -------- | ------- | ----------- |
| Safari 6.1+ | iPad 3+ |  iOS 8+ |
| Google Chrome 32+ |  Android 4.3+ | Android 4.3+ |
| Internet Explorer 11+ |  |  |
| Firefox 27+ | | |

## Built With

- [Ruby on Rails](https://github.com/rails/rails) &mdash; Our back end API is a Rails app. It responds to requests RESTfully in JSON.
- [Ember.js](https://github.com/emberjs/ember.js) &mdash; Our front end is an Ember.js app that communicates with the Rails API.
- [PostgreSQL](http://www.postgresql.org/) &mdash; Our main data store is in Postgres.
- [Redis](http://redis.io/) &mdash; We use Redis as a cache and for transient data.

Plus *lots* of Ruby Gems, a complete list of which is at [/master/Gemfile](https://github.com/discourse/discourse/blob/master/Gemfile).

## Copyright / License

Copyright 2014 - 2017 Civilized Discourse Construction Kit, Inc.

Licensed under the GNU General Public License Version 2.0 (or later);
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Discourse logo and “Discourse Forum” ®, Civilized Discourse Construction Kit, Inc.

## Dedication

Discourse is built with [love, Internet style.](http://www.youtube.com/watch?v=Xe1TZaElTAs)
