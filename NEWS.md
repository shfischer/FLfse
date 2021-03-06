NEWS
================

## Version 1.0

### Changes since version 0.x

Changes to `SAM2FLStock`

-   Fix when SAM model fit included age 0 but without catches for this
    age.

-   Fix setting of plusgroup.

-   New arguments `mat_est`, `stock.wt_est`, `catch.wt_est`, `m_est`
    (logical `TRUE`/`FALSE`) for returning estimates of biological data
    from SAM, if they are estimated by SAM.

-   New argument `spinoutyear` (logical `TRUE`/`FALSE`) to
    include/exclude estimates of biological data from SAM beyond last
    data year.

-   Generic methods for `SAM2FLStock` updated when argument `stk` is
    provided as a template. In the returned output, `stk` is used as
    template and all slots are updated, instead of only those
    corresponding to catch, fishing mortality and stock size.

Changes to `SAM_uncertainty`

-   Name of output list element with catch numbers including uncertainty
    changed from `catch_n` to `catch.n` so that it follows the same
    convention as `stock.n`.

General changes

-   Updated help files.
