---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

// Dependencies
using Microsoft.Graph.Beta.Models;

var requestBody = new User
{
	DisplayName = "Test User",
	Identities = new List<ObjectIdentity>
	{
		new ObjectIdentity
		{
			SignInType = "emailAddress",
			Issuer = "contoso.onmicrosoft.com",
			IssuerAssignedId = "adelev@adatum.com",
		},
	},
	Mail = "adelev@adatum.com",
	PasswordProfile = new PasswordProfile
	{
		Password = "passwordValue",
		ForceChangePasswordNextSignIn = true,
	},
	PasswordPolicies = "DisablePasswordExpiration",
};

// To initialize your graphClient, see https://learn.microsoft.com/en-us/graph/sdks/create-client?from=snippets&tabs=csharp
var result = await graphClient.Users.PostAsync(requestBody);


```