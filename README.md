## README
Rails has a bunch of ways to update Database column, here is the cheatsheet to help developers save more time.


| Method           | Uses Default Accessor | Saved to Database | Validations | Callbacks | Touches updated_at | Readonly check |
|------------------|-----------------------|-------------------|-------------|-----------|--------------------|----------------|
| attribute=       | Yes                   | No                | n/a         | n/a       | n/a                | n/a            |
| write_attribute  | No                    | No                | n/a         | n/a       | n/a                | n/a            |
| update_attribute | Yes                   | Yes               | No          | Yes       | Yes                | Yes            |
| attributes=      | Yes                   | No                | n/a         | n/a       | n/a                | n/a            |
| update           | Yes                   | Yes               | Yes         | Yes       | Yes                | Yes            |
| update_column    | No                    | Yes               | No          | No        | No                 | Yes            |
| update_columns   | No                    | Yes               | No          | No        | No                 | Yes            |
| User::update     | Yes                   | Yes               | Yes         | Yes       | Yes                | Yes            |
| User::update_all | No                    | Yes               | No          | No        | No                 | No             |

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/fifiteen82726/RailsAttributesSheet. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

## License

The gem is available as open source under the terms of the MIT License.


## TODO
### Further way
`assign_attributes`
`write_attribute`

### Further Example
