This folder contains all the data related to the raspberry application.

The two log files are output from "vmstat -t 1".
The "marketplace_trace.log" is an exctract of what have been recorded while the Raspberry was running the StakeCube node. Most notably, it shows the CPU spike when a new block is created.
The baseline log has been recorded right after the node execution. This is needed to accurately measure StakeCube's inpact, because vmstat only provides system-wide statistics.
The "run_data" folder shows the output of the marketplace application. It contains:
 * The list of blocks, including header, transactions, and certificate.
 * The output of the pseudo-smartcontract, i.e., a  list of matches. A Match is a pair of two bids: an ask and a buy. A bid contains a price, quantity and sender.
