# Identity Blockchain

## About

IdentityBlockchain uses state-certified electronic identities (eIDs) to establish blockchain identities and a consensus protocol called Proof of Identity (PoI). 

PoI is ”green” and enables many applications that are impossible to implement without verified identity on the blockchain, e.g., direct democracy and universal basic income, encrypted messaging, etc.

IdentityBlockchain, as presented here, aims to preserve identity anonymity by using zk-SNARKs and an anonymizing protocol for identity onboarding.

IdentityBlockchain will be a fork of Avalanche blockchain based on PoI.

The material that follows is under construction, bit it can offer a glimpse into the overlying ideas and concepts.

## Description

### Notation

| Symbol      | Meaning     |
| :---        |    :----:   |
| Header      | Title       |
| Paragraph   | Text        |

<table style="width:91%;">
<colgroup>
<col style="width: 36%" />
<col style="width: 55%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="text-align: left;"></td>
<td style="text-align: left;">State CA certified public key of e.g.
eID</td>
</tr>
<tr class="even">
<td style="text-align: left;"><span
class="math inline">\(K(value)\)</span></td>
<td style="text-align: left;"><span class="math inline">\(value\)</span>
encrypted with the public key <span
class="math inline">\(K\)</span>.</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><span
class="math inline">\(\kid^{-1}\)</span></td>
<td style="text-align: left;">Private key corresponding to the public
key <span class="math inline">\(K\)</span>.</td>
</tr>
<tr class="even">
<td style="text-align: left;"></td>
<td style="text-align: left;">Person key, used to access PeopleBC as an
unknown Person.</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><span
class="math inline">\(H\)</span></td>
<td style="text-align: left;">SHA256</td>
</tr>
</tbody>
</table>
