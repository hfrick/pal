# errors informatively on .pal_app error

    Code
      .init_addin()
    Condition
      Error:
      ! some error

# errors informatively with missing binding

    Code
      .init_addin()
    Condition
      Error:
      ! Unable to locate the requested pal.

# .init_addin executes found binding

    Code
      res <- .init_addin()
    Message
      howdy!
