# [`@exodus/schemasafe`](https://github.com/ExodusMovement/schemasafe) - test summary


# [`@exodus/schemasafe`](https://github.com/ExodusMovement/schemasafe) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`@exodus/schemasafe`](https://github.com/ExodusMovement/schemasafe) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`anyOf with boolean schemas, all true, any value is valid`|The schema failed to load(`some checks are never reachable at #`)
`anyOf with boolean schemas, some true, any value is valid`|The schema failed to load(`some checks are never reachable at #`)
`anyOf with one empty schema, string is valid`|The schema failed to load(`some checks are never reachable at #`)
`anyOf with one empty schema, number is valid`|The schema failed to load(`some checks are never reachable at #`)
`validation of IDN e-mail addresses, ignores integers`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN e-mail addresses, ignores floats`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN e-mail addresses, ignores objects`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN e-mail addresses, ignores arrays`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN e-mail addresses, ignores booleans`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN e-mail addresses, ignores null`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of IDN hostnames, ignores integers`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IDN hostnames, ignores floats`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IDN hostnames, ignores objects`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IDN hostnames, ignores arrays`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IDN hostnames, ignores booleans`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IDN hostnames, ignores null`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IRIs, ignores integers`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, ignores floats`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, ignores objects`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, ignores arrays`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, ignores booleans`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, ignores null`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRI references, ignores integers`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI references, ignores floats`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI references, ignores objects`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI references, ignores arrays`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI references, ignores booleans`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI references, ignores null`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`if with boolean schema true, boolean schema true in if always chooses the then path (valid)`|The schema failed to load(`some checks are never reachable at #`)
`if with boolean schema true, boolean schema true in if always chooses the then path (invalid)`|The schema failed to load(`some checks are never reachable at #`)
`if with boolean schema false, boolean schema false in if always chooses the else path (invalid)`|The schema failed to load(`some checks are never reachable at #`)
`if with boolean schema false, boolean schema false in if always chooses the else path (valid)`|The schema failed to load(`some checks are never reachable at #`)
`not with boolean schema false, any value is valid`|The schema failed to load(`some checks are never reachable at #`)
`oneOf with boolean schemas, one true, any value is valid`|The schema failed to load(`some checks are never reachable at #`)
`oneOf with boolean schemas, more than one true, any value is invalid`|The schema failed to load(`some checks are never reachable at #`)
`oneOf with boolean schemas, all false, any value is invalid`|The schema failed to load(`some checks are never reachable at #`)
`validation of an internationalized e-mail addresses, a valid idn e-mail (example@example.test in Hangul)`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of an internationalized e-mail addresses, an invalid idn e-mail address`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of an internationalized e-mail addresses, a valid e-mail address`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of an internationalized e-mail addresses, an invalid e-mail address`|The schema failed to load(`Unrecognized format used: "idn-email" at #`)
`validation of internationalized host names, a valid host name (example.test in Hangul)`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, illegal first char U+302E Hangul single dot tone mark`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, contains illegal char U+302E Hangul single dot tone mark`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, a host name with a component too long`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, invalid label, correct Punycode`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, valid Chinese Punycode`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, invalid Punycode`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, U-label contains "--" in the 3rd and 4th position`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, U-label starts with a dash`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, U-label ends with a dash`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, U-label starts and ends with a dash`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Begins with a Spacing Combining Mark`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Begins with a Nonspacing Mark`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Begins with an Enclosing Mark`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Exceptions that are PVALID, left-to-right chars`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Exceptions that are PVALID, right-to-left chars`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Exceptions that are DISALLOWED, right-to-left chars`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Exceptions that are DISALLOWED, left-to-right chars`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, MIDDLE DOT with no preceding 'l'`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, MIDDLE DOT with nothing preceding`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, MIDDLE DOT with no following 'l'`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, MIDDLE DOT with nothing following`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, MIDDLE DOT with surrounding 'l's`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Greek KERAIA not followed by Greek`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Greek KERAIA not followed by anything`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Greek KERAIA followed by Greek`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERESH not preceded by Hebrew`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERESH not preceded by anything`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERESH preceded by Hebrew`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERSHAYIM not preceded by Hebrew`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERSHAYIM not preceded by anything`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Hebrew GERSHAYIM preceded by Hebrew`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, KATAKANA MIDDLE DOT with no Hiragana, Katakana, or Han`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, KATAKANA MIDDLE DOT with no other characters`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, KATAKANA MIDDLE DOT with Hiragana`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, KATAKANA MIDDLE DOT with Katakana`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, KATAKANA MIDDLE DOT with Han`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Arabic-Indic digits mixed with Extended Arabic-Indic digits`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Arabic-Indic digits not mixed with Extended Arabic-Indic digits`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, Extended Arabic-Indic digits not mixed with Arabic-Indic digits`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, ZERO WIDTH JOINER not preceded by Virama`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, ZERO WIDTH JOINER not preceded by anything`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, ZERO WIDTH JOINER preceded by Virama`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, ZERO WIDTH NON-JOINER preceded by Virama`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of internationalized host names, ZERO WIDTH NON-JOINER not preceded by Virama but matches regexp`|The schema failed to load(`Unrecognized format used: "idn-hostname" at #`)
`validation of IRI References, a valid IRI`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, a valid protocol-relative IRI Reference`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, a valid relative IRI Reference`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, an invalid IRI Reference`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, a valid IRI Reference`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, a valid IRI fragment`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRI References, an invalid IRI fragment`|The schema failed to load(`Unrecognized format used: "iri-reference" at #`)
`validation of IRIs, a valid IRI with anchor tag`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, a valid IRI with anchor tag and parantheses`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, a valid IRI with URL-encoded stuff`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, a valid IRI with many special characters`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, a valid IRI based on IPv6`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, an invalid IRI based on IPv6`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, an invalid relative IRI Reference`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, an invalid IRI`|The schema failed to load(`Unrecognized format used: "iri" at #`)
`validation of IRIs, an invalid IRI though valid IRI reference`|The schema failed to load(`Unrecognized format used: "iri" at #`)

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)