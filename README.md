# Mybatis 3

This project is modified based on [mybatis/mybatis-3](https://github.com/mybatis/mybatis-3), version 3.2.7.

Original project is licensed under the Apache License, Version 2.0.

## 🔧 Modifications
- Back to 3.2.7 version to using java version 6
- Change query log level to INFO from DEBUG at PreparedStatementLogger
- Delete query log at ConnectionLogger
- Delete query parameter log at PreparedStatementLogger
- Add query log with parameter at PreparedStatementLogger
- Display query parameter value instead of '?'
- Display query log pretty

## License

This project remains under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), originally authored by the MyBatis project.