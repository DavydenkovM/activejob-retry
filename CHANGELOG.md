## 0.4.2 - March 22, 2015

- Remove Sidekiq from the problematic adapter blacklist (patch by [@troter](https://github.com/troter))

## 0.4.1 - March 18, 2015

- Remove the need for an explicit require (patch by [@isaacseymour](https://github.com/isaacseymour))

## 0.4.0 - January 16, 2015

- Blacklist problematic adapters rather than whitelisting known good ones (patch by [@isaacseymour](https://github.com/isaacseymour))

## 0.3.1 - January 6, 2015

- Internal code tidy up

## 0.3.0 - January 6, 2015

- `rescue_from` gets called only when all retries have failed, rather than before attempting to retry (patch by [@isaacseymour](https://github.com/isaacseymour))

## 0.2.0 - January 1, 2015

- Renamed retry_exceptions to retryable_exceptions (patch by [@greysteil](https://github.com/greysteil))

## 0.1.1 - January 1, 2015

- Initial release
