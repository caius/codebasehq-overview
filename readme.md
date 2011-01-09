# CodebaseHQ Overview

"Simple" HTML file with some javascript contained therein that lets you see all tickets (assigned to you) across all projects in your [codebasehq](http://codebasehq.com/) account.

To use it you need your: subdomain, username and api token. You can find your api token on your "My Settings" page.

## API Request Limit

Due to the way it has to iterate over all your projects, then all statuses/tickets/priorities/categories within those projects it ends up using 25 API Requests to load the page once. By default you only get 80 api requests with codebase. This means you can load this script 3 times in an hour before you start getting api rate limit errors returned.

## Todo

* Finish filtering tickets to those assigned to you and not considered closed
* Display data on the page once we've grabbed it
