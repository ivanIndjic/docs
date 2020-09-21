
---
title: "GetConnectionType"
title_tag: "Function GetConnectionType | Module automation | Package Azure NextGen"
meta_desc: "Explore the GetConnectionType function of the automation module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using GetConnectionType {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getConnectionType<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetConnectionTypeArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx">GetConnectionTypeResult</span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_connection_type(</span><span class="nx">automation_account_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">connection_type_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetConnectionTypeResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupConnectionType<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx">LookupConnectionTypeArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx">LookupConnectionTypeResult</span>, error)</span></code></pre></div>

> Note: This function is named `LookupConnectionType` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetConnectionType </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx">GetConnectionTypeResult</span>> <span class="p">InvokeAsync(</span><span class="nx">GetConnectionTypeArgs</span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="automationaccountname_csharp">
<a href="#automationaccountname_csharp" style="color: inherit; text-decoration: inherit;">Automation<wbr>Account<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the automation account.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="connectiontypename_csharp">
<a href="#connectiontypename_csharp" style="color: inherit; text-decoration: inherit;">Connection<wbr>Type<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of connection type.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_csharp">
<a href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Name of an Azure Resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="automationaccountname_go">
<a href="#automationaccountname_go" style="color: inherit; text-decoration: inherit;">Automation<wbr>Account<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the automation account.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="connectiontypename_go">
<a href="#connectiontypename_go" style="color: inherit; text-decoration: inherit;">Connection<wbr>Type<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of connection type.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_go">
<a href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Name of an Azure Resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="automationaccountname_nodejs">
<a href="#automationaccountname_nodejs" style="color: inherit; text-decoration: inherit;">automation<wbr>Account<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the automation account.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="connectiontypename_nodejs">
<a href="#connectiontypename_nodejs" style="color: inherit; text-decoration: inherit;">connection<wbr>Type<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of connection type.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Name of an Azure Resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="automation_account_name_python">
<a href="#automation_account_name_python" style="color: inherit; text-decoration: inherit;">automation_<wbr>account_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the automation account.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="connection_type_name_python">
<a href="#connection_type_name_python" style="color: inherit; text-decoration: inherit;">connection_<wbr>type_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of connection type.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resource_group_name_python">
<a href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Name of an Azure Resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## GetConnectionType Result {#result}

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="creationtime_csharp">
<a href="#creationtime_csharp" style="color: inherit; text-decoration: inherit;">Creation<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="fielddefinitions_csharp">
<a href="#fielddefinitions_csharp" style="color: inherit; text-decoration: inherit;">Field<wbr>Definitions</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, Pulumi.<wbr>Azure<wbr>Next<wbr>Gen.<wbr>Automation.<wbr>Outputs.<wbr>Field<wbr>Definition<wbr>Response&gt;</span>
    </dt>
    <dd>{{% md %}}Gets the field definitions of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the name of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Resource type{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_csharp">
<a href="#description_csharp" style="color: inherit; text-decoration: inherit;">Description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the description.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="isglobal_csharp">
<a href="#isglobal_csharp" style="color: inherit; text-decoration: inherit;">Is<wbr>Global</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets a Boolean value to indicate if the connection type is global.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodifiedtime_csharp">
<a href="#lastmodifiedtime_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the last modified time.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="creationtime_go">
<a href="#creationtime_go" style="color: inherit; text-decoration: inherit;">Creation<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="fielddefinitions_go">
<a href="#fielddefinitions_go" style="color: inherit; text-decoration: inherit;">Field<wbr>Definitions</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type">map[string]Field<wbr>Definition<wbr>Response</span>
    </dt>
    <dd>{{% md %}}Gets the field definitions of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the name of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Resource type{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_go">
<a href="#description_go" style="color: inherit; text-decoration: inherit;">Description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the description.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="isglobal_go">
<a href="#isglobal_go" style="color: inherit; text-decoration: inherit;">Is<wbr>Global</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets a Boolean value to indicate if the connection type is global.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodifiedtime_go">
<a href="#lastmodifiedtime_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the last modified time.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="creationtime_nodejs">
<a href="#creationtime_nodejs" style="color: inherit; text-decoration: inherit;">creation<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="fielddefinitions_nodejs">
<a href="#fielddefinitions_nodejs" style="color: inherit; text-decoration: inherit;">field<wbr>Definitions</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: Field<wbr>Definition<wbr>Response}</span>
    </dt>
    <dd>{{% md %}}Gets the field definitions of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets the name of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Resource type{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_nodejs">
<a href="#description_nodejs" style="color: inherit; text-decoration: inherit;">description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the description.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="isglobal_nodejs">
<a href="#isglobal_nodejs" style="color: inherit; text-decoration: inherit;">is<wbr>Global</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets a Boolean value to indicate if the connection type is global.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodifiedtime_nodejs">
<a href="#lastmodifiedtime_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified<wbr>Time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the last modified time.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="creation_time_python">
<a href="#creation_time_python" style="color: inherit; text-decoration: inherit;">creation_<wbr>time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Gets the creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="field_definitions_python">
<a href="#field_definitions_python" style="color: inherit; text-decoration: inherit;">field_<wbr>definitions</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Field<wbr>Definition<wbr>Response]</span>
    </dt>
    <dd>{{% md %}}Gets the field definitions of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Gets the name of the connection type.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Resource type{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_python">
<a href="#description_python" style="color: inherit; text-decoration: inherit;">description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the description.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="is_global_python">
<a href="#is_global_python" style="color: inherit; text-decoration: inherit;">is_<wbr>global</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets a Boolean value to indicate if the connection type is global.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="last_modified_time_python">
<a href="#last_modified_time_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified_<wbr>time</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the last modified time.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types


<h4 id="fielddefinitionresponse">Field<wbr>Definition<wbr>Response</h4>







{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the type of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isencrypted_csharp">
<a href="#isencrypted_csharp" style="color: inherit; text-decoration: inherit;">Is<wbr>Encrypted</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isEncrypted flag of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isoptional_csharp">
<a href="#isoptional_csharp" style="color: inherit; text-decoration: inherit;">Is<wbr>Optional</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isOptional flag of the connection field definition.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the type of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isencrypted_go">
<a href="#isencrypted_go" style="color: inherit; text-decoration: inherit;">Is<wbr>Encrypted</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isEncrypted flag of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isoptional_go">
<a href="#isoptional_go" style="color: inherit; text-decoration: inherit;">Is<wbr>Optional</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isOptional flag of the connection field definition.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the type of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isencrypted_nodejs">
<a href="#isencrypted_nodejs" style="color: inherit; text-decoration: inherit;">is<wbr>Encrypted</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isEncrypted flag of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isoptional_nodejs">
<a href="#isoptional_nodejs" style="color: inherit; text-decoration: inherit;">is<wbr>Optional</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isOptional flag of the connection field definition.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the type of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="isoptional_python">
<a href="#isoptional_python" style="color: inherit; text-decoration: inherit;">is<wbr>Optional</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isOptional flag of the connection field definition.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="is_encrypted_python">
<a href="#is_encrypted_python" style="color: inherit; text-decoration: inherit;">is_<wbr>encrypted</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Gets or sets the isEncrypted flag of the connection field definition.{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-nextgen">https://github.com/pulumi/pulumi-azure-nextgen</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>
