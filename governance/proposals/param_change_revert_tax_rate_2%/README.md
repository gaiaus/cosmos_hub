


[param_change_revert_tax_rate_2p.json](https://github.com/gaiaus/cosmos_hub/blob/main/governance/proposals/param_change_revert_tax_rate_2%25/param_change_revert_tax_rate_2p.json) 

This is the valid JSON structure used to successfully submit [Proposal 966](https://www.mintscan.io/cosmos/proposals/996/) on Cosmos Hub 4 (running Gaia v23). 

Key requirements:

  - Proposal content is wrapped in a top-level messages array
  -  Module-specific message type is specified via @type field
  - The authority field contains the governance module's authority address
  - Required metadata fields include" deposit", "proposer", "title", and "summary"
  - The "description" metadata field is now defunct

[legacy_proposal_test.json](https://github.com/gaiaus/cosmos_hub/blob/main/governance/proposals/param_change_revert_tax_rate_2%25/legacy_proposal_test.json)

This legacy format is no longer valid in Cosmos SDK v50.0+ and Gaia v23. This older structure was deprecated when the Cosmos Hub migrated to the new module-specific MsgUpdateParams.

 Note the following structural differences from the current implementation:

  - Each parameter change specified the module via a subspace field
  - Parameter keys followed a different naming convention (e.g., communitytax vs. the current community_tax)
  - The format only required specifying parameters that were being changed, rather than the full parameter set
  - No authority field was required to authorize the change

