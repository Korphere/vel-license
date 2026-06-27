# Voluntary Enterprise License (VEL)

VEL is a highly flexible, dual-license abstraction framework that allows open-source creators to capture corporate funding through voluntary contract procurement, without sacrificing the viral adoption of permissive open-source licenses.

## The Template Core (vel-effortless)

```markdown
# Voluntary Enterprise License (VEL)

This project is dual-licensed under the **{uncommercial-license-name}** and the **Commercial Support License**.
You can freely choose whichever fits your situation.

---

## 1. Open-Source Option: {uncommercial-license-name}

{uncommercial-license-content}

---

## 2. Enterprise Option: Commercial Support License
(Designed for enterprises requiring compliance records, custom invoicing, formal procurement paths, or wishing to sponsor ongoing development)

### 2.1. Grant of License
By opting for this Commercial Support License and completing the designated payment, the Licensor grants your organization a formal, documented right to utilize, modify, and distribute the software within your enterprise environment. This option includes:
- **Compliance Receipt:** Issuance of a formal invoice, receipt, or subscription record suitable for corporate accounting.
- **Sustainability Contribution:** Direct financial support toward the maintenance, security, and future development of the software.

### 2.2. Pricing & Terms
- **Fee:** Minimum {price} / {period} (or any higher voluntary contribution to support the project).
- **Termination:** This commercial option remains valid for the duration of the paid {period} and may be renewed continuously.

### 2.3. Warranty & Liability
STRICTLY ZERO. To the maximum extent permitted by applicable law, the software is provided "AS IS", without warranty of any kind. In no event shall the authors, copyright holders, or the organization be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software.

## 2.4 Benefits

For information on the benefits included with the purchase of a commercial license, please refer to `BENEFITS.md`.
```

## Why VEL? (The Psychological Inversion)
Permissive licenses like MIT expose creators to zero-compensation corporate exploitation. Copyleft licenses like AGPL scare away enterprise legal teams, killing ecosystem adoption.

VEL solves this by providing a dual track. Enterprise legal compliance teams actively reject "Free" software due to liability audit rules; they **require a paid receipt** to clear internal procurement. VEL turn this corporate constraint into an automated sponsorship loop. You provide the required paper trail (Corporate License Track) with **Strictly Zero Liability**, while keeping the codebase 100% plug-and-play free for individual geeks via the Permissive Track.

## About `BENEFITS.md`

`BENEFITS.md` lists the benefits included with the purchase of a commercial license for those who wish to have flexibility in making changes. For example:
- Display of your name or logo based on the purchase amount
- Priority support
and so on.
I've included an example of the content in [benefits/BENEFITS.example.md](https://github.com/Korphere/vel-license/tree/main/benefits/BENEFITS.example.md), so please refer to that.

### Regarding the inclusion of benefits such as the display of a name and logo

We recommend listing names and logos in `BACKER.md`. This is because listing all sponsor names and logos in the README or similar documents can make it difficult to access the “Product Description” and “Get Started” sections—which are the primary purposes of these files—and may result in lower product adoption rates. However, it should be fine as long as it does not hinder access, such as by listing only the product’s largest sponsor in the README.


## Get Started
1. Copy the template above into your repository as `LICENSE` or `LICENSE.md`.
2. Inject your preferred open-source base license into `{uncommercial-license-name}` (MIT, Apache 2.0, BSD, etc.) (already in `apache-v2-with-vel-effortless.md`, `mit-with-vel-effortless.md`, `2-clause-bsd-with-vel-effortless.md` and `3-clause-bsd-with-vel-effortless.md`.)
3. Define you own price, period, and unique `{original-guarantee}` (`{original-guarantee}` is not required)

### ⚠️ Important Notice for `vel-with-warranty-and-liability-provisions-removed`

The `vel-with-warranty-and-liability-provisions-removed` template intentionally omits the "STRICTLY ZERO" warranty and liability clauses from the Enterprise Option.

**Use this template ONLY if you are signing a separate, explicit contract (such as a Master Services Agreement, SLA, or Custom NDA/Liability Agreement) with the enterprise client.**

By entirely removing the liability disclaimer from the license itself, local laws in many jurisdictions may automatically impose implied warranties (e.g., obligations to fix bugs, or financial liability for damages caused by the software). If you are simply providing a compliance receipt or offering standard sponsorships without a separate legal contract, **do not use this template**. Please use `vel-effortless` or `vel-effortless-with-original-guarantee` instead to protect yourself from unlimited liability.

## Disclaimer

The VEL (Voluntary Enterprise License) framework, including all templates, examples, and accompanying documentation provided in this repository, is intended for informational and educational purposes only and **does not constitute legal advice**. 

The authors and contributors of this repository are not lawyers, and the use of this framework does not create an attorney-client relationship. You are solely responsible for your use of these templates. It is strongly recommended that you consult with a qualified legal professional before applying these licenses to your software to ensure they meet your specific legal, compliance, and business requirements.

To the maximum extent permitted by applicable law, the authors and contributors disclaim all liability for any direct, indirect, incidental, or consequential damages, or any legal disputes, arising out of or in connection with the use, modification, or distribution of this framework. **Use at your own risk.**