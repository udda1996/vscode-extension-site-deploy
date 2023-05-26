# Design using the Architecture Diagram

The Architecture View includes a range of editing capabilities that makes it possible to design projects via the diagram. The sections below explore these capabilities by executing the **Architecture View** command on an empty workspace.

## Add components

As prompted above, you can use the **Add Component** option to add the first component of your project as shown below. 

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/add-component.gif" class="cInlineImage-full"/>

!!! Info
    If your project has components, you can use the **Add Component** option on the top left corner of the diagram to do the same.

## Delete components

If any other component in your project is not dependent on a particular component, you can delete them using the **Delete Component** option available on the node menu (seen on hover of a node). This option will provide you with two choices: either to delete only the particular service or to delete the entire Ballerina package.

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/delete-component.gif" class="cInlineImage-full"/>

## Link to an internal API

You can create links between your project components using the **Use Internal API** option in the node menu. This will introduce a service-level client in your source service, which you can configure and use thereafter.

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/internal-linking.gif" class="cInlineImage-full"/>

## Link to an external API

You can invoke an external endpoint using the **Use External API** option in the node menu. This will prompt you to a connector marketplace from which you can choose the required external endpoint.

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/external-linking.gif" class="cInlineImage-full"/>

## Delete links

By hovering over a link, you can choose to remove the particular interaction in your diagram. This will result in the deletion of the client that was used to interact between the services.

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/delete-links.gif" class="cInlineImage-full"/>

## Edit diagram labels

You can edit the display names of your project components using the **Edit Label** option in the node menu. This will update the **label** value of the particular component’s display annotation.

<img src="https://wso2.com/ballerina/vscode/docs/img/visual-programming/architecture-view/architecture-diagram/edit-label.gif" class="cInlineImage-full"/>
