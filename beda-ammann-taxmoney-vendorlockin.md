Sciences Po Paris, Introduction to Digital Common, Beda Ammann, 28.12.25.
# Are you using taxpayers' money efficiently?
## Vendor lock-In lessons with respect to Switzerland's EMBAG law
Open source software (OSS) and code hold massive potential for government institutions. The Swiss government recognized this in 2023 by making it the default under EMBAG (Federal Act on the Use of Electronic Means for the Fulfilment of Administrative Tasks) Art. 9: publicly funded software must be released openly unless third-party rights or security issues arise. This shift ensures that taxpayer money is used eXiciently through transparency (external code audits) and cost-sharing (code reuse). Most importantly, however, it gives sovereignty to the users with full data and code control, thereby preventing them from vendor lock-in.[1] This essay shows how the Swiss example of EMBAG and the practical implementation of OSS can reduce vendor lock-in better than proprietary models elsewhere.

## Proprietary Traps: NHS, Czech Ministries, and "$1 Pilots"
Adam Duraj's "Vendor lock-in in IT procurement" reveals the problems of vendor lock-in with examples drawn from Czech IT procurement, highlighting systematic flaws in proprietary IT procurement without OSS defaults. He emphasizes that the EU public sector loses €1.1 billion annually to proprietary dependencies and examines Czech ministries that exemplify these "unswitchable" traps. For example, the Czech Ministry of Finance bought an IBM system for over €120 million, with the contract being prolonged through a "negotiated procedure without publication" even though the system is not further developed or evolved.[2]

Samantha Niblett brought the problem of vendor lock-in to the British parliament: "Microsoft has ripped oX the NHS (National Health Service)", highlighting how the company secures initial deals with attractive pricing, only to trap government departments into expensive, ongoing arrangements. She criticizes that the British government spends such large amounts of money on Microsoft. The new deal with the NHS is worth £700 million, while the government already bought Microsoft software licences in 2024-2025 for £1.9 billion.[3]

OpenAI is using the same strategy of attractive initial pricing to push governments to use its model ChatGPT, for $1 a year. Nicolas Chaillan warns that this strategy targets federal agencies by embedding workflows, making switching diXicult and cost-intensive once users are trained.[4] Then companies raise prices. Government bodies lose their flexibility and must pay the demanded price to keep their work running, even though more modern technological solutions may exist.

## Switzerland's EMBAG
The Swiss EMBAG targets this kind of lock-in described above. Not directly through prohibiting the use of proprietary models, but through advocating OSS solutions. Article 9 makes open source the default for federal software, requiring that source code developed with public funds be published so anyone can use, adapt, and redistribute it. Instead of accepting “too expensive to switch” as a given, EMBAG assumes from the start that software will become part of a shared digital commons.

The inosca consortium is an example demonstrating what this may look like in practice. In the very fragmented federal system of Switzerland, several cantons share a common open source platform for electronic building permits, with the code on GitHub. Rather than each canton negotiating its own proprietary solution, they reuse and improve one shared codebase, cutting duplication and avoiding vendor lock-in. Through the broadly supported initiative, they also minimize the risk that the code is not further maintained after publication, one core risk of OSS.[5]

Furthermore, the Bern University of Applied Sciences (BFH) was tasked by a federal agency to examine practical implementation options for open source alternatives. Standtke and Tiede show that for most of the proprietary software solutions in the Swiss federal administration, OSS alternatives exist. They identify, for example, the following open source replacements for central Microsoft services: Univention UCS for directory services, Nextcloud/ONLYOFFICE for collaboration, and OpenXchange or Zimbra for email. According to their calculations, switching costs roughly €17 million per 10,000 users, which could be more cost-eXective than paying licence fees after only a short amount of time.[6]
## Conclusion
Although not directly banning proprietary systems in the federal administration, EMBAG has opened the discussion about the broader use of open source products. The credo is: when public money is used for development, it should be used as eXiciently as possible. First initiatives with implementations are already being used, such as inosca. However, the potential to use open source products in the federal administration and save money is still enormous, as Standke and Tiede show. Other governmental bodies, such as the NHS or Czech ministries described above, still lose millions locked into proprietary models. Switzerland serves as an example of clear legal regulation of publicly funded OSS, ensuring the eXective usage of taxpayers' money and technological sovereignty.

## Bibliography
[1] D. T. and I. S. S. D. Federal Chancellery, “Em002-1 Practical Guidelines for Open Source Software in the Federal Administration.” Feb. 24, 2025.

[2] A. Duraj, “Vendor lock-in in IT procurement.” Charles University in Prague, May 17, 2017.

[3] A. Rose, “‘Microsoft overcharged NHS’, say MPs as they slam £700 million deal,” Eastern Eye, Nov. 21, 2025. [Online]. Available: https://www.easterneye.biz/microsoft-nhs-mp-cybersecurity-public-sector/

[4] N.Chaillan,“TheRealCostofVendorLock-In:WhyGovernmentNeedsSmarterTech Partnerships,” Government Technology Insider, 22.08.22025. [Online]. Available: https://governmenttechnologyinsider.com/the-real-cost-of-vendor-lock-in-why- government-needs-smarter-tech-partnerships/

[5] inosca, “inosca - Interkantonale Entwicklungsgemeinschaft für elektronische Bewilligungsprozesse.” [Online]. Available: https://inosca.ch

[6] R. Standtke and M. Tiede, “Studie zu Open-Source-Alternativen von Microsoft Services und Produkten in der Schweizerischen Bundesverwaltung.” Berner Fachhochschule, Feb. 2024.
