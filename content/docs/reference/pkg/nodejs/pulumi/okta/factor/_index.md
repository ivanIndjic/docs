---
title: "Module factor"
title_tag: "Module factor | Package @pulumi/okta | Node.js SDK"
linktitle: "factor"
meta_desc: "Explore members of the factor module in the @pulumi/okta package."
git_sha: "d8223ec34121f866677918fc6244e020f13ce023"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "okta" >}}




<h3>Resources</h3>
<ul class="api">
    <li><a href="#Factor"><span class="symbol resource"></span>Factor</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#FactorArgs"><span class="symbol api"></span>FactorArgs</a></li>
    <li><a href="#FactorState"><span class="symbol api"></span>FactorState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Factor" data-link-title="Factor">
    <a href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L23">
        Resource <strong>Factor</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Factor</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Allows you to manage the activation of Okta MFA methods.

This resource allows you to manage Okta MFA methods.

#### Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as okta from "@pulumi/okta";

const example = new okta.factor.Factor("example", {
    providerId: "google_otp",
});
```

<h4 class="pdoc-member-header" id="Factor-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L59"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Factor(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#FactorArgs'>FactorArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Factor resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Factor-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L33">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#FactorState'>FactorState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Factor'>Factor</a></code></pre>


Get an existing Factor resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Factor-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L23">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Factor-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L44">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): obj is Factor</code></pre>


Returns true if the given object is an instance of Factor.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Factor-active">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L54">property <b>active</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>active: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Whether or not to activate the provider, by default it is set to `true`.

<h4 class="pdoc-member-header" id="Factor-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L23">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Factor-providerId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L59">property <b>providerId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>providerId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The MFA provider name.
Allowed values are `"duo"`, `"fidoU2f"`, `"fidoWebauthn"`, `"googleOtp"`, `"oktaCall"`, `"oktaOtp"`, `"oktaPush"`, `"oktaQuestion"`, `"oktaSms"`, `"rsaToken"`, `"symantecVip"` or `"yubikeyToken"`.

<h4 class="pdoc-member-header" id="Factor-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L23">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="FactorArgs" data-link-title="FactorArgs">
    <a href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L112">
        interface <strong>FactorArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>FactorArgs</span></code></pre>

The set of arguments for constructing a Factor resource.

<h4 class="pdoc-member-header" id="FactorArgs-active">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L116">property <b>active</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>active?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>

Whether or not to activate the provider, by default it is set to `true`.

<h4 class="pdoc-member-header" id="FactorArgs-providerId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L121">property <b>providerId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>providerId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The MFA provider name.
Allowed values are `"duo"`, `"fidoU2f"`, `"fidoWebauthn"`, `"googleOtp"`, `"oktaCall"`, `"oktaOtp"`, `"oktaPush"`, `"oktaQuestion"`, `"oktaSms"`, `"rsaToken"`, `"symantecVip"` or `"yubikeyToken"`.

<h3 class="pdoc-module-header" id="FactorState" data-link-title="FactorState">
    <a href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L97">
        interface <strong>FactorState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>FactorState</span></code></pre>

Input properties used for looking up and filtering Factor resources.

<h4 class="pdoc-member-header" id="FactorState-active">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L101">property <b>active</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>active?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>

Whether or not to activate the provider, by default it is set to `true`.

<h4 class="pdoc-member-header" id="FactorState-providerId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-okta/blob/d8223ec34121f866677918fc6244e020f13ce023/sdk/nodejs/factor/factor.ts#L106">property <b>providerId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>providerId?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The MFA provider name.
Allowed values are `"duo"`, `"fidoU2f"`, `"fidoWebauthn"`, `"googleOtp"`, `"oktaCall"`, `"oktaOtp"`, `"oktaPush"`, `"oktaQuestion"`, `"oktaSms"`, `"rsaToken"`, `"symantecVip"` or `"yubikeyToken"`.

