# <%= (string-capitalize (getf env :name)) %><% @if description %> - <% @var description %><% @endif %>

## Usage

## Installation
<%- @if author %>

## License

Licensed under the <% @var license %> License.
<%- @endif %>
