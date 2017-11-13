## Secrets via keyring library

Secret data, such as login cookies and league IDs are managed via keyring.
See https://github.com/jaraco/keyring

Before running scripts, set these secrets via the keyring cli:
`keyring set fantasy_playoffs cookies_espn_s2`
`keyring set fantasy_playoffs cookies_swid`
`keyring set fantasy_playoffs league_id`
