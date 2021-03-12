# mga

http://codematters.tech/getting-access-token-for-microsoft-graph-using-oauth-rest-api/


https://login.microsoftonline.com/256d2b4c-b5c3-758f-55f3-cd8969f04e86/oauth2/token

https://login.microsoftonline.com/{TenantDirectory}.onmicrosoft.com/adminconsent?client_id={ApplicationID}
https://docs.microsoft.com/en-us/graph/auth-v2-service

http://xqting.com/msgraphandmsalinjavaformsteams

https://medium.com/@fiqriismail/how-to-get-an-access-token-for-microsoft-graph-api-using-node-js-258723f29cc6


ClientCredentialProvider authProvider = new ClientCredentialProvider(
            this.clientId,
            this.scopes,
            this.clientSecret,
            this.tenantId,
            this.endpoint);
IGraphServiceClient graphClient = GraphServiceClient
            .builder()
            .authenticationProvider(authProvider)
            .buildClient();

https://stackoverflow.com/questions/61807289/microsoft-graph-api-getting-access-without-a-user-in-java/61819800#61819800




https://stackoverflow.com/questions/7929369/how-to-rebase-local-branch-onto-remote-master/18442755#18442755
