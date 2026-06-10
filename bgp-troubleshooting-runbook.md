# BGP Troubleshooting Runbook

## Objective

Identify and resolve BGP neighbor and routing issues.

## Common Issues

- BGP neighbor down
- Route advertisement failures
- Route flapping
- Incorrect AS numbers
- Filtering issues

## Verification Commands

### Cisco

show ip bgp summary

show ip bgp neighbors

show ip route bgp

### Juniper

show bgp summary

show route protocol bgp

## Troubleshooting Steps

1. Verify IP connectivity between peers
2. Verify BGP neighbor configuration
3. Check AS numbers
4. Verify route filters and prefix lists
5. Review route advertisements
6. Check interface status and packet loss

## Expected Results

- Neighbor state = Established
- Routes received successfully
- Routes advertised successfully

## Lessons Learned

Document root cause and resolution.
