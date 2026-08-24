# Reference
## gateway
<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">listModels</a>() -> DtgAgentSdk.ModelList</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.listModels();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">createChatCompletion</a>({ ...params }) -> DtgAgentSdk.ChatCompletion</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.createChatCompletion({
    model: "model",
    messages: [{
            role: "system",
            content: "content"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.ChatCompletionRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## agents
<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">listAgents</a>() -> DtgAgentSdk.ListAgentsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.listAgents();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">createAgent</a>({ ...params }) -> DtgAgentSdk.CreateAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.createAgent({
    display_name: "display_name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.AgentCreateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">getAgent</a>({ ...params }) -> DtgAgentSdk.GetAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.getAgent({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.GetAgentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">deleteAgent</a>({ ...params }) -> DtgAgentSdk.DeleteAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.deleteAgent({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.DeleteAgentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">updateAgent</a>({ ...params }) -> DtgAgentSdk.UpdateAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.updateAgent({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.AgentUpdateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">startAgent</a>({ ...params }) -> DtgAgentSdk.StartAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.startAgent({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.StartAgentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">stopAgent</a>({ ...params }) -> DtgAgentSdk.StopAgentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.stopAgent({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.StopAgentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">getAgentChannels</a>({ ...params }) -> DtgAgentSdk.GetAgentChannelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.getAgentChannels({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.GetAgentChannelsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">updateAgentChannels</a>({ ...params }) -> DtgAgentSdk.UpdateAgentChannelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.updateAgentChannels({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.UpdateAgentChannelsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agents.<a href="/src/api/resources/agents/client/Client.ts">listAgentModels</a>() -> DtgAgentSdk.ModelList</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.agents.listAgentModels();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AgentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## api-keys
<details><summary><code>client.apiKeys.<a href="/src/api/resources/apiKeys/client/Client.ts">listApiKeys</a>() -> DtgAgentSdk.ListApiKeysResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.apiKeys.listApiKeys();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ApiKeysClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.apiKeys.<a href="/src/api/resources/apiKeys/client/Client.ts">createApiKey</a>({ ...params }) -> DtgAgentSdk.CreateApiKeyResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.apiKeys.createApiKey({
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.ApiKeyCreateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ApiKeysClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.apiKeys.<a href="/src/api/resources/apiKeys/client/Client.ts">revokeApiKey</a>({ ...params }) -> DtgAgentSdk.RevokeApiKeyResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.apiKeys.revokeApiKey({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.RevokeApiKeyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ApiKeysClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## organizations
<details><summary><code>client.organizations.<a href="/src/api/resources/organizations/client/Client.ts">getOrganization</a>({ ...params }) -> DtgAgentSdk.GetOrganizationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizations.getOrganization({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.GetOrganizationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizations.<a href="/src/api/resources/organizations/client/Client.ts">listOrganizationMembers</a>({ ...params }) -> DtgAgentSdk.ListOrganizationMembersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizations.listOrganizationMembers({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.ListOrganizationMembersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## knowledge
<details><summary><code>client.knowledge.<a href="/src/api/resources/knowledge/client/Client.ts">listKnowledge</a>() -> DtgAgentSdk.ListKnowledgeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.knowledge.listKnowledge();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `KnowledgeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.knowledge.<a href="/src/api/resources/knowledge/client/Client.ts">createKnowledge</a>({ ...params }) -> DtgAgentSdk.CreateKnowledgeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.knowledge.createKnowledge({
    title: "title",
    content: "content"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.KnowledgeCreateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `KnowledgeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.knowledge.<a href="/src/api/resources/knowledge/client/Client.ts">getKnowledge</a>({ ...params }) -> DtgAgentSdk.GetKnowledgeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.knowledge.getKnowledge({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.GetKnowledgeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `KnowledgeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.knowledge.<a href="/src/api/resources/knowledge/client/Client.ts">deleteKnowledge</a>({ ...params }) -> DtgAgentSdk.DeleteKnowledgeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.knowledge.deleteKnowledge({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.DeleteKnowledgeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `KnowledgeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## mcp-servers
<details><summary><code>client.mcpServers.<a href="/src/api/resources/mcpServers/client/Client.ts">listMcpServers</a>() -> DtgAgentSdk.ListMcpServersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.mcpServers.listMcpServers();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `McpServersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.mcpServers.<a href="/src/api/resources/mcpServers/client/Client.ts">createMcpServer</a>({ ...params }) -> DtgAgentSdk.CreateMcpServerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.mcpServers.createMcpServer({
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.McpServerCreateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `McpServersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.mcpServers.<a href="/src/api/resources/mcpServers/client/Client.ts">listMcpServerTools</a>({ ...params }) -> DtgAgentSdk.ListMcpServerToolsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.mcpServers.listMcpServerTools({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.ListMcpServerToolsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `McpServersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.mcpServers.<a href="/src/api/resources/mcpServers/client/Client.ts">createMcpServerTool</a>({ ...params }) -> DtgAgentSdk.CreateMcpServerToolResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.mcpServers.createMcpServerTool({
    id: "id",
    body: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `DtgAgentSdk.CreateMcpServerToolRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `McpServersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

