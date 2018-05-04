# Curl Collisions

This project provides an efficient implementation of Heilman et al.'s collision attack on Iota's now deprecated hash function, Curl. It can be used to generate novel collisions in the hash funciton in minutes to hours depending on hardware. Please see our report for a detailed coverage of the methodology behind its implementation.

## Example collisions

```
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTXMDZMMVEVVCTQFRTMDR9QLPG9QUWBHBQBVOPDWDIOFUWBK9IREKOUVRHDODLLXCLMJWZZXENYXDUSVDGU)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTXMDZMMVEVVCTQFRTMDR9QLPG9QUWBHBQBVOPDWDIOGUWBK9IREKOUVRHDODLLXCLMJWZZXENYXDUSVDGU)=
BUEXRNXFUP9HUMBOJWJZBQKDTZKOUVUXSJAXGKMNH9I9EWNBXPBCFNEPBFCQFDYZZCBMXOTP9DOIMKEZ9

hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTFYYHYMOGOVCTIYRVML9IKFSGCPSYBK9RDKNGBTVXIRIB9FBJOPLPUKRQMLVUOXDGKGDZ9FWWEXDXGJPYU)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTFYYHYMOGOVCTIYRVML9IKFSGCPSYBK9RDKNGBTVXISIB9FBJOPLPUKRQMLVUOXDGKGDZ9FWWEXDXGJPYU)=
XYXHZSVKLZFZQSLXCGSDZHYLPBNXVIDUMPTCWKUZSDPQMTETH9UFHPQAAWLNE9PTR9KBITPUU9ZOQXBTZ

hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTLGGEAMPJQQDUZERLMKRXNXDS9OUDDKY9KKYNKTYU99IWWFXHPGLELTRRGOAIL9DMJH9Y9GOGEEMXSMDPR)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTLGGEAMPJQQDUZERLMKRXNXDS9OUDDKY9KKYNKTYU9AIWWFXHPGLELTRRGOAIL9DMJH9Y9GOGEEMXSMDPR)=
UT9GBOHGMYVVMXPDQWVDIZFDLFUGI9XNSL9LVTGKKLMBBJTBQ9PGDXGXLPHOQFPIMNIZAPHSIAVRDV9BX

hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTISJNJGNFTPXNANSTMCRIKXMJXRNXAIBZUDONDBMXUXFBAJCMUPTGVV9QDRGIXCWJKIBDZFXYOYMUSDGPU)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTISJNJGNFTPXNANSTMCRIKXMJXRNXAIBZUDONDBMXUYFBAJCMUPTGVV9QDRGIXCWJKIBDZFXYOYMUSDGPU)=
DHSPNMAPHELGLFBRXBGXN9NLLLRVQRPZYN9NVKLOXSIJQ9NVGOQBIUPVRSBQRDCMBQMIBTIMIHKPWLHWU

hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTFDVNYJTHVN9SQYZTVVICZCVACPQWDLYJCDEXLWDUUOCZ9MWLNEVETBQAGOARRXDIGIXYQEPGPEVIYMADU)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTFDVNYJTHVN9SQYZTVVICZCVACPQWDLYJCDEXLWDUUPCZ9MWLNEVETBQAGOARRXDIGIXYQEPGPEVIYMADU)=
GJXEJZISSTXJGLS99RVEFHOZJITZWCRDFVTDSAYGNBMMXSYXNRXPHRYPDIZWFILJDBV9QVHMIOAUSINNB

hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTLSVNSGRLSUZNROAVKM9OZOGMCQSXBJY9KLNYVQYUUUUWAEYFNWCOKURQJFV9RXCKKLB9RXGXGNVOPAVGU)=
hash(ACMUXEIFDOIVQMVZNXPNWGSA9JGCN9RIMWOYNFLAVLBKRJPKRAYFCGSD9CAJEFVPHIWRZEKQHUHCAKKSTLSVNSGRLSUZNROAVKM9OZOGMCQSXBJY9KLNYVQYUUVUWAEYFNWCOKURQJFV9RXCKKLB9RXGXGNVOPAVGU)=
LRK9AHITJUEMPFCPVGFUZRNVWIF9TSYOJROYAZBENSWGSC9PDIHUAPKFTJECCPLOWJHSLW9SOTQQ9EKIP
```

## Collaborators
- Michael Colavita
- Garrett Tanzer
