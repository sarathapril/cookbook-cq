# v1.2.0 (2018-12-02)

* [#68](https://github.com/jwadolowski/cookbook-cq/pull/68) New resource: `cq_start_guard`
* [#69](https://github.com/jwadolowski/cookbook-cq/pull/69) `cq_start_guard` docs
* [#71](https://github.com/jwadolowski/cookbook-cq/pull/71) Documentation improvements
* [#72](https://github.com/jwadolowski/cookbook-cq/pull/72) New resource: `cq_clientlib_cache`

# v1.1.2 (2018-07-02)

* [#67](https://github.com/jwadolowski/cookbook-cq/pull/67) Amazon Linux support

# v1.1.1 (2018-04-27)

* Bugfix in RHEL detection

# v1.1.0 (2018-04-17)

* [#66](https://github.com/jwadolowski/cookbook-cq/pull/66) systemd service (default on CentOS/RHEL 7)
* [#66](https://github.com/jwadolowski/cookbook-cq/pull/66) Chef 13.x and 14.x support
* AEM 5.6.1 and 6.0.0 are no longer supported

# v1.0.1 (2018-04-11)

* Git reference to CQ UNIX Toolkit cookbook was removed from `Berksfile`, as it
  is available on Supermarket now

# v1.0.0 (2018-04-10)

First public release of CQ cookbook!

Supported AEM versions:

* AEM 5.6.1
* AEM 6.0.0
* AEM 6.1.0
* AEM 6.2.0
* AEM 6.3.0
* AEM 6.4.0

Supported operating systems:

* CentOS/RHEL 6.x
* CentOS/RHEL 7.x

Custom resources:

* `cq_package`
* `cq_osgi_config`
* `cq_osgi_bundle`
* `cq_osgi_component`
* `cq_user`
* `cq_jcr`

At the time of writing `chef-client` 12.20.3 is recommended. Official support
for 13.x and 14.x will be added in the upcoming releases.
