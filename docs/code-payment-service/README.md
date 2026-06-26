# Documentation for code-payment-service (production)

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *AppApi* | [**appControllerGetRoot**](Apis/AppApi.md#appControllerGetRoot) | **GET** /code-payment-service |  |
| *PaymentControllersApi* | [**paymentCallbackControllerHandleCallbackGet**](Apis/PaymentControllersApi.md#paymentCallbackControllerHandleCallbackGet) | **GET** /code-payment-service/subscriptions/payment-callback/{provider} |  |
*PaymentControllersApi* | [**paymentCallbackControllerHandleCallbackPost**](Apis/PaymentControllersApi.md#paymentCallbackControllerHandleCallbackPost) | **POST** /code-payment-service/subscriptions/payment-callback/{provider} |  |
*PaymentControllersApi* | [**paymentReturnControllerHandleReturnGet**](Apis/PaymentControllersApi.md#paymentReturnControllerHandleReturnGet) | **GET** /code-payment-service/subscriptions/payment-return/{provider} |  |
*PaymentControllersApi* | [**paymentReturnControllerHandleReturnPost**](Apis/PaymentControllersApi.md#paymentReturnControllerHandleReturnPost) | **POST** /code-payment-service/subscriptions/payment-return/{provider} |  |
| *PlansApi* | [**archivePlanControllerExecute**](Apis/PlansApi.md#archivePlanControllerExecute) | **DELETE** /code-payment-service/plans/{plan_id} |  |
*PlansApi* | [**createPlanControllerExecute**](Apis/PlansApi.md#createPlanControllerExecute) | **POST** /code-payment-service/plans |  |
*PlansApi* | [**getAllPlanControllerExecute**](Apis/PlansApi.md#getAllPlanControllerExecute) | **GET** /code-payment-service/plans |  |
| *SubscriptionsApi* | [**getMySubscriptionControllerExecute**](Apis/SubscriptionsApi.md#getMySubscriptionControllerExecute) | **GET** /code-payment-service/subscriptions |  |
*SubscriptionsApi* | [**getTransactionHistoryControllerExecute**](Apis/SubscriptionsApi.md#getTransactionHistoryControllerExecute) | **GET** /code-payment-service/subscriptions/history |  |
*SubscriptionsApi* | [**manualActivateTransactionControllerExecute**](Apis/SubscriptionsApi.md#manualActivateTransactionControllerExecute) | **POST** /code-payment-service/subscriptions/manual-activate/{transaction_id} |  |
*SubscriptionsApi* | [**purchaseSubscriptionControllerExecute**](Apis/SubscriptionsApi.md#purchaseSubscriptionControllerExecute) | **POST** /code-payment-service/subscriptions/purchase |  |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [CreatePlanRequestDto](./Models/CreatePlanRequestDto.md)
 - [PurchaseSubscriptionRequestDto](./Models/PurchaseSubscriptionRequestDto.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="HTTPBearer"></a>
### HTTPBearer

- **Type**: HTTP Bearer Token authentication (JWT)

