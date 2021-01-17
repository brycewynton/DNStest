# DNStest
Simple DNS script for testing response times.

# to see a list of current DNS providers enter:

  scutil --dns

# If DNS poisoning is suspected, flush cache with:

  dscacheutil -flushcache

  sudo killall -HUP mDNSResponder
