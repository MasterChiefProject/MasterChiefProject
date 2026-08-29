GitHub profile README update
Repository: MasterChiefProject/MasterChiefProject

Recommended header asset:
  assets/profile-header.gif

The GIF is the safest option for GitHub because the flag animation is baked into the image.
The SVG version is included as an editable/vector alternative.

1) Replace the existing capsule-render header line with:

<img width="100%" src="assets/profile-header.gif" alt="Daniel Adin profile header with waving Israeli flag"/>

2) In 05 // EDUCATION & RECORDS, replace the current animated record line with:

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2450&pause=850&color=A7C957&center=true&vCenter=true&width=900&lines=ACADEMIC+%26+SERVICE+RECORDS+%2F%2F+DOCUMENTED;B.SC.+COMPUTER+SCIENCE+%2F%2F+COMPLETED+2026;IDF+MILITARY+SERVICE+%2F%2F+HONORABLE+DISCHARGE;FULL+ISRAELI+BAGRUT+%2F%2F+COMPLETED+2019;TECHNICAL+RESUME+%2F%2F+AVAILABLE" alt="Animated education, service, and document record"/>

3) Add this row to the records table after the B.Sc. row and before the Bagrut row:

<tr>
<td align="center" width="28%">
<sub>SERVICE RECORD</sub><br/>
<strong>Israel Defense Forces</strong>
</td>
<td align="center" width="24%">
<sub>SERVICE</sub><br/>
<strong>Military Service</strong>
</td>
<td align="center" width="16%">
<sub>STATUS</sub><br/>
<strong>Honorable Discharge</strong>
</td>
<td align="center" width="32%">
<sub>DOCUMENT</sub><br/><br/>
<a href="docs/idf_certificate_of_honorable_discharge.pdf">
  <img src="https://img.shields.io/badge/VIEW-SERVICE%20CERTIFICATE-0038B8?style=flat-square&labelColor=0B1110" alt="IDF certificate of honorable discharge"/>
</a>
</td>
</tr>

4) Commit both README.md and assets/profile-header.gif.

Suggested commit message:
Update profile records and animated Israel header
