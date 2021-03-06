# Standards

![screws in all shapes and sizes](screws.jpg)

<https://raw.github.com/xi/standards_talk/2013-11-13/standards.htm>

# What is a standard?

-   A (technical) specification is a standard if it is widely established.
-   It may be a *de facto* or *de jure* standard, where only the latter has
    gone through a formal standardization process with an established
    standardization organisation.
-   A standard therefore needs legitimacy


# parties involved

stakeholders
:   anyone with an interest in a proposed standard
implementors
:   anyone who will implement (parts of) the standard
users
:   anyone who might use an implementation
sponsor
:   proposes a specification for standardization

# parties involved

standardization organisation
:   organisation which manages the standardization process
working group (WG)
:   the people who manage the standardization process
    for the *standardization organisation*
advisors/experts
:   external people who are asked to participate in the standardization
    process. May be members of the *working group*


# open standard

-   anyone (especially implementors) have unrestricted access
    (e.g. no fees or classification)
-   free implementations must exist
-   anyone can participate in the creation and further development of the standard

<http://documentfreedom.org/openstandards.html>
<http://www.csrstds.com/openstds.html>


# decentralization

-   hacker ethics call for decentralization
-   standards provide ways for decentralizing technology
-   at the same time, the standardization process itself is
    necessarily centralized
-   everyone respects standards
-   very few people know how standards are created


# overview of standardization organisations

# International Organisation for Standardization (ISO)

-   ISO 639 – Codes for the representation of names of languages (de_DE)
-   ISO 8601 – Representation of dates and times (1999-12-31 23:59:58)
-   ISO/IEC 8859 – 8-bit single-byte coded graphic character sets

# International Organisation for Standardization (ISO)

-   ISO/IEC 26300 – Open Document Format for Office Applications (OpenDocument) v1.0
-   ISO/IEC 29500 – Office Open XML File Formats

# International Organisation for Standardization (ISO)

-   "network of national standards bodies"
-   specs are not open (fees)
-   only member organisations are allowed to vote
-   "fast-track procedure" possible if the document was developed by an
    international standardizing body recognized by the ISO Council


# Deutsches Institut für Normung (DIN)

-   german member of ISO
-   DIN 476 (ISO 216): international paper sizes


# Institute of Electrical and Electronics Engineers (IEEE)

-   IEEE 802.x – networking
-   IEEE 1003 – Unix compatibility programming standard - POSIX
-   allowed to vote is "any individual who has expressed an interest in the subject matter of the standard"


# Internet Engineering Task Force (IETF)

-   RFC 1034/1035 DNS
-   RFC 1157 IMAP
-   RFC 2616 HTTP
-   RFC 2821 SMTP

# Internet Engineering Task Force (IETF)

-   RFC 1149 IP on Avian Carriers (Pidgins)
-   RFC 2324 Hyper Text Coffee Pot Control Protocol

# Internet Engineering Task Force (IETF)

-   Request for Comments (RFC)
-   "rough consensus and running code"
-   discussion on archived mailing lists


# World Wide Web Consortium (W3C)

-   founded and headed by Tim Berners-Lee
-   HTML/CSS
-   WCAG/ARIA (Accessibility)

# World Wide Web Consortium (W3C)

Working Draft
:   anyone is asked for comment
Candidate Recommendation
:   implementors are asked for feedback
Proposed Recommendation
:   W3C advisory council is asked to approve
W3C Recommendation
:   process is completed

# World Wide Web Consortium (W3C)

-   no certification program, but free validators
-   members are mostly big companies like IBM, Google, Facebook, Deutsche Telekom etc.
-   discussion on archived mailing lists
-   Possible to submit bugs from draft (Example: [HTML5 draft](http://www.w3.org/html/wg/drafts/html/master/))


# Web Hypertext Application Technology Working Group (WHAT WG)

-   formed when W3C was moving in a different direction than implementors
-   HTML5

# python/bittorrent

-   [PEP](http://www.python.org/dev/peps/pep-0001/)/[BEP](http://bittorrent.org/beps/bep_0001.html)
    (Python/BitTorrent Enhancement Proposals)
-   "rough consensus and running code"
-   author responsible for building consensus
-   open source reference implementation needed
-   spec must be in public domain
-   Benevolent Dictator for Life, Guido van Rossum/Bram Cohen


# summary: standardization process

-   someone proposes a draft
-   it must be accepted for consideration
-   a working group may be formed
-   the process may go through several phases getting inputs from the general public, experts and implementors

# summary: standardization process

-   a high majority or even consensus is required
-   additional requirements (e.g. reference implementation)
-   the final vote is on a closed group of people, e.g. benevolent dictators or member organisations


# critique

> [...] the ostensibly open process of the W3C actually isn’t open: It’s
> dominated by multinationals; the opinions of everyone other than invited
> experts can be and are ignored; invited-expert status has been refused or
> revoked; the Working Group can claim that “consensus” has been reached even
> in the face of unresolved internal disagreement; the process is itself
> inaccessible to people with disabilities, like deaf people; WCAG Working
> Group chairs have acted like bullies.
> -- <http://www.wcagsamurai.org/erratas/introduction/>


# What we can learn from this

-   standards as an unusual product of an participation process
-   decision making in a given process needs to be standardized
-   most current standardization processes are optimized for output
    legitimacy by providing enough resources to reach a high
    quality specification, maybe even a consensus
-   discussions are done using bug-trackers, mailinglists and
    long dicussions


# What we can provide for this

-   a better tool for proposing alternative versions and commenting (*absatzweise Kommentieren*)
-   reaching consensus in long meetings and discussions is currently
    out of our scope
