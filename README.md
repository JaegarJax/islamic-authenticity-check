# Islamic Authenticity Check

A Claude skill that answers Islamic questions and checks whether things are halal, **strictly according to the Salafi manhaj**: the Qur'an and the authentic Sunnah as understood by the Salaf, explained through trusted Salafi scholars.

## What it does

For every question it gives:
1. **The ruling in short**
2. **The evidence** from the Qur'an (Surah:Ayah) and authentic Sunnah, with each hadith's grade and who graded it
3. **What the scholars said**, quoting their fatwa with a link to the exact page or book
4. **How confident it is**, and when to ask a scholar directly

It never invents a fatwa, a hadith, a grading or a link. For serious personal matters (divorce, inheritance, takfir, major contracts) it refers you to a qualified Salafi scholar.

## Scholars and sources used (and only these)

- Shaykh al-Islam Ibn Taymiyyah, Ibn al-Qayyim, Shaykh Muhammad ibn Abd al-Wahhab
- Shaykh Ibn Baz — binbaz.org.sa
- Shaykh Ibn Uthaymeen — binothaimeen.net
- Shaykh Salih al-Fawzan — alfawzan.af.org.sa
- al-Lajnah al-Da'imah and the Council of Senior Scholars — alifta.gov.sa
- Shaykh al-Albani (hadith grading)
- Shaykh Muqbil al-Wadi'i, Shaykh Rabee' al-Madkhali, Shaykh Abd al-Muhsin al-Abbad
- Shaykh Othman al-Khamis, Shaykh Abdulaziz al-Anazi
- islamqa.info (references the above), dorar.net (hadith gradings)

## Not used

No Shia, Alawite, Druze, Sufi, Baha'i, Ahmadi, Ash'ari/Maturidi, modernist or other sect's sources, and not al-Azhar or Dar al-Ifta al-Misriyyah.

## Install

**Claude Code:** copy the `islamic-authenticity-check` folder into `~/.claude/skills/`.

**Claude.ai / Claude app:** download `islamic-authenticity-check.skill` from the Releases page (or zip the folder) and upload it under Settings → Capabilities → Skills.

Works best with web search turned on, so it can open the scholars' sites and link the exact fatwa.

## Disclaimer

This is a research helper, not a mufti. Always confirm important matters with a qualified scholar. والله أعلم
