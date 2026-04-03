# Ork Tzeentch Daemon Encounter Log

An on-chain ledger of Ork descriptions of encounters with Tzeentch’s daemons,  
sorcerous cults, warp-mutants, fire-spittin' horrors, and reality-bendin' tricksters.

Each entry uses a short 3‑line format describing how da weird ladz acted  
and how da scrap ended. The community votes whether the encounter was  
**WAAAGH-approved** or **not proppa'.**

---

## Contract

Deployed on Base:  
`0xb3778bA8F87059e13AE37E87C08420A33AddBC2F`  
https://basescan.org/address/0xb3778ba8f87059e13ae37e87c08420a33addbc2f#code

Main file: `contracts/TzeentchDaemonEncounterLog.sol`

---

## Example encounter

```solidity
recordEncounter(
  "Pink Horror Mob",
  "Da pink gitz danced around shootin' warp-fire an' laughin' like dey knew a joke we didn't.",
  "Da scrap ended wiv more pink, more blue, an' da boyz swearin' dey multiplied when we hit 'em."
);

Voting
voteEncounter(1, true);   // WAAAGH-approved
voteEncounter(1, false);  // Not proppa'


Closing Note
A chaotic chronicle of da Changer of Ways —
da laughy ones, da burny ones,
an' da ones dat split into more gitz when ya smash 'em.
