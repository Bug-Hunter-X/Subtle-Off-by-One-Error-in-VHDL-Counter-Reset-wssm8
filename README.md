# Subtle Off-by-One Error in VHDL Counter Reset

This repository demonstrates a common, subtle off-by-one error that can occur in VHDL when implementing counters.  The `buggy_counter.vhd` file contains the flawed code. The counter fails to reset correctly at its maximum value.  The `fixed_counter.vhd` file provides the corrected implementation.

The bug is a classic example of how a small mistake in the conditional logic can lead to unexpected behavior in a digital design.  Care must be taken when designing counters, particularly when dealing with edge-sensitive processes and reset conditions.