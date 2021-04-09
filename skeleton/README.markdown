# <%= (string-capitalize (getf env :name)) %><% @if description %> - <% @var description %><% @endif %>

## Usage

## Installation
<%- @if author %>

## Copyright

Copyright (c) <%= (local-time:timestamp-year (local-time:now)) %> <% @var author %><% @if email %> (<% @var email %>)<% @endif %>
<%- @endif %>
<%- @if license %>

## License

Licensed under the <% @var license %> License.
<%- @endif %>
