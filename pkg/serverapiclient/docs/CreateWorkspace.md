# CreateWorkspace

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**Repositories** | Pointer to **[]string** |  | [optional] 

## Methods

### NewCreateWorkspace

`func NewCreateWorkspace() *CreateWorkspace`

NewCreateWorkspace instantiates a new CreateWorkspace object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWorkspaceWithDefaults

`func NewCreateWorkspaceWithDefaults() *CreateWorkspace`

NewCreateWorkspaceWithDefaults instantiates a new CreateWorkspace object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateWorkspace) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWorkspace) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWorkspace) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateWorkspace) HasName() bool`

HasName returns a boolean if a field has been set.

### GetProvider

`func (o *CreateWorkspace) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateWorkspace) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateWorkspace) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *CreateWorkspace) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetRepositories

`func (o *CreateWorkspace) GetRepositories() []string`

GetRepositories returns the Repositories field if non-nil, zero value otherwise.

### GetRepositoriesOk

`func (o *CreateWorkspace) GetRepositoriesOk() (*[]string, bool)`

GetRepositoriesOk returns a tuple with the Repositories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepositories

`func (o *CreateWorkspace) SetRepositories(v []string)`

SetRepositories sets Repositories field to given value.

### HasRepositories

`func (o *CreateWorkspace) HasRepositories() bool`

HasRepositories returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

