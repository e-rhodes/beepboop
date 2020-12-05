# beepboop
beep boop bop ding ding whirr

To compile:

    cargo build --release

If you have cargo installed, you can run with:

    cargo run [files]

Otherwise, a binary is provided in `./target/release`, which can be run with

    ./target/release/beepboop [files]

Beepboop code files can be found in the `code` folder.


## Basics

Integer literals are created in a binary representation, where beep represents a 1 and boop represents zero. E.g. 13 could be represented as `beep beep boop beep`.

Variable assignment:

    whirr <var> <value>


If statement:

    bip <condition> <value_if_true> <value_if_false>

The `condition` can be either a boolean or a number (where 0 represents false, and anything else is true).

For loop:

    ratatat <n_loops> <body>


## Math
Addition:

    plop <a> <b>

Multiplication:

    ting <a> <b>


## Logic
And:

    zap <a> <b>

Or:

    zorp <a> <b>

Greater than:

    zeep <a> <b>

Less than:

    zip <a> <b>

Equal:

    bzz <a> <b>



