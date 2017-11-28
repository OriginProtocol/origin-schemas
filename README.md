# listing-schemas

We're using [JSONSchema](http://json-schema.org/) as the base data structure for Origin listings. 

Since many unrelated developers will be reading and writing to
the same data layer, it is essential that everyone adhere to common standards.
We will publish and maintain the rules for what constitutes a “valid Origin
listing” as well as a library of inheritable JSON schemas for fields commonly
used on listings, such as email addresses, URLs, GPS coordinates, international
street addresses, international phone numbers and other metadata. These schemas
are also easily extensible enabling the creation of new product categories,
support for internationalization or other languages as well as other unforeseen
use-cases.

You can see some basic example schemas in this repo. More formalized standards will be published soon.
