# 0.2.1
 * Use new MKSTREAM on Redis consumer group instead of wrapping failure
# 0.2.0
 * Add a supervisor for each consumer
 * Handle shutdown of a consumer gracefully
# 0.1.6/7
 * Fix typespecs around mfa() and handler()
# 0.1.5
 * Remove deprecated `Supervisor.Spec` usage
# 0.1.4
 * Bump up dependencies to redix 0.8.2
# 0.1.3
 * Bump up dependencies to Elixir 1.7 and redix 0.7.1
# 0.1.2
 * Added official Redis consumer group support (thanks @jeffutter)
# 0.1.1
 * Added a simple tracker concept to allow for safe consumer restarts.
# 0.1.0
 * Initial version