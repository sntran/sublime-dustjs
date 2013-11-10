sublime-dustjs
==============

Dust.js support for Sublime Text.

### How to use

Dust.js support  will be active for any `*.dust` file, or by choosing “Set Syntax: Dust.js Template” in the Command Palette.

Type one of the these triggers – followed by <kbd>tab</kbd> or <kbd>ctrl+tab</kbd> – to insert a snippets.

<table align="center">
    <thead>
        <tr>
            <th>Trigger</th>
            <th>Meaning</th>
            <th>Snippet</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>dc</code></td>
            <td>
                <b>d</b>ust <b>c</b>omment
            </td>
            <td>
                <code>{! ... !}</code>
            </td>
        </tr>
        <tr>
            <td><code>ds</code></td>
            <td>
                <b>d</b>ust <b>s</b>ection
            </td>
            <td>
                <code>{#section}...{/section}</code>
            </td>
        </tr>
        <tr>
            <td><code>dn</code></td>
            <td>
                <b>d</b>ust <b>n</b>o
            </td>
            <td><code>{^name}...{/name}</code></td>
        </tr>
        <tr>
            <td><code>dy</code></td>
            <td>
                <b>d</b>ust <b>y</b>es
            </td>
            <td><code>{?name}...{/name}</code></td>
        </tr>
        <tr>
            <td><code>dp</code></td>
            <td>
                <b>d</b>ust <b>p</b>artial
            </td>
            <td><code>{>partial}...{/partial}</code></td>
        </tr>
        <tr>
            <td><code>db</code></td>
            <td>
                <b>d</b>ust <b>b</b>lock
            </td>
            <td><code>{>block}...{/block}</code></td>
        </tr>
        <tr>
            <td><code>deq</code></td>
            <td>
                <b>d</b>ust <b>eq</b>uals
            </td>
            <td><code>{@eq}...{:else}...{/eq}</code></td>
        </tr>
        <tr>
            <td><code>dne</code></td>
            <td>
                <b>d</b>ust <b>n</b>ot <b>e</b>quals
            </td>
            <td><code>{@ne}...{:else}...{/ne}</code></td>
        </tr>
        <tr>
            <td><code>dlt</code></td>
            <td>
                <b>d</b>ust <b>l</b>ess <b>t</b>han
            </td>
            <td><code>{@lt}...{:else}...{/lt}</code></td>
        </tr>
        <tr>
            <td><code>dlte</code></td>
            <td>
                <b>d</b>ust <b>l</b>ess <b>t</b>han or <b>e</b>quals
            </td>
            <td><code>{@lte}...{:else}...{/lte}</code></td>
        </tr>
        <tr>
            <td><code>dgt</code></td>
            <td>
                <b>d</b>ust <b>g</b>reater <b>t</b>han
            </td>
            <td><code>{@gt}...{:else}...{/gt}</code></td>
        </tr>
        <tr>
            <td><code>dgte</code></td>
            <td>
                <b>d</b>ust <b>g</b>reater <b>t</b>han or <b>e</b>quals
            </td>
            <td><code>{@gte}...{:else}...{/gte}</code></td>
        </tr>
         <tr>
            <td><code>dmath</code></td>
            <td>
                <b>d</b>ust <b>math</b>
            </td>
            <td><code>{@math key="..." method="..." ...}</code></td>
        </tr>
        <tr>
            <td><code>dsel</code></td>
            <td>
                <b>d</b>ust <b>sel</b>ect
            </td>
            <td><code>{@select}...{/select}</code></td>
        </tr>
    </tbody>
</table>

---


Written in JSON and used [AAAPackageDev](https://bitbucket.org/guillermooo/aaapackagedev) to convert to plist.

Completions are inspired by [SublimeHTMLMustache](https://github.com/adamchainz/SublimeHTMLMustache).