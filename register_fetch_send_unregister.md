# Blockwise transfer
coap && coap.opt.block_number

# CoAP filter for Register Fetch Send Unregister
coap && (udp.srcport == 59615 || udp.dstport == 59615)

