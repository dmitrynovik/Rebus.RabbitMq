# Changelog

## 2.0.0-a1

* Test release

## 2.0.0-a2

* Update RabbitMQ client dependency to 4.0.1
* Update target framework to .NET 4.5.2

## 2.0.0-b01

* Test release

## 2.0.0-b02

* More convenient namespaces

## 2.0.0

* Release 2.0.0

## 3.0.0

* Update to Rebus 3

## 4.0.0

* Update to Rebus 4
* Add .NET Core support (netstandard1.5)

## 4.1.0

* Change node failover strategy to rely on built-in capabilities of the driver - thanks [samartzidis]

## 4.1.1

* Fix credentials issue - thanks [samartzidis]

## 4.1.2

* Fix weird dependency on NUnit test adapter - thanks [bzuu]

## 4.2.0

* Add support for priority queues (requires RabbitMQ 3.5) - thanks [K3llr]
* Ability to configure SSL settings - thanks [nebelx]

## 4.3.0

* Additional configuration overloads to allow for passing custom connection information to the RabbitMQ connection factory - thanks [nebelx]

## 4.4.0

* Update RabbitMQ client dependency to v. 5.0.1 - thanks [dougkwilson]

## 4.4.1

* Handle `SecurityException` when trying to figure out which machine we're running on - thanks [samartzidis]

## 4.4.2

* Minor tweak to avoid potential dictionary trouble with double-adding - thanks [samartzidis]


---

[bzuu]: https://github.com/bzuu
[dougkwilson]: https://github.com/dougkwilson
[nebelx]: https://github.com/nebelx
[K3llr]: https://github.com/K3llr
[samartzidis]: https://github.com/samartzidis