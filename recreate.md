# Phase 1: Linux Command Line CTF Challenge
This set of progressive Capture The Flag (CTF) challenges will test your Linux command line skills. Each challenge builds upon previous concepts while introducing new ones. All flags follow the format `CTF{some_text_here}`.
> [!IMPORTANT] <br>
> Please complete [Phase 1 Guide][def] before attempting these challenges. Do not share solutions publicly - focus on sharing your learning journey instead.

[def]: https://learntocloud.guide/phase1/

## Flag Submission
Submit flags using the `verify` command:
- Check progress: `verify progress`
- Submit a flag: `verify [challenge_number] [flag]`
- Test the system: `verify 0 CTF{example}`

Example: `verify 0 CTF{example}`

```
ctf_user@ctf-vm:~$ verify 0 CTF{example}
✓ Example flag verified! Now try finding real flags.
```

## Environment Setup
Follow the setup guide for your preferred cloud provider:
- [AWS][def2]
- [Azure][def3]

[def2]: ./aws/README.md
[def3]: ./azure/README.md

## Challenges
NOTE: You should be able to complete all challenges in about 2 to 3 hours. The lab is intentionally made to be done in one go. If you power off the VM and power it back on, certain challenges (specifically challenges 6, 10, 11, and 12) will not work properly as they depend on running services.
 ### Challenge 1: The Hidden file