
# UI 
form: 
https://ant.design/components/form/#components-form-demo-basic


# auth
Now, we base on the nextjs-antd project, and add auth feature.

For our use case, we only consider username & password in local database. So, we use the 
credential project in the next-auth.js.

1. 


npm install next-auth --save
npm install axios --save

add pages/api/[..nextauth].js file





import { Provider } from 'next-auth/client'



# Redirect after login

set in the auth.js:

callbackUrl: `${window.location.origin}/welcome`




# ref

https://dev.to/twisha/using-credentials-provider-with-a-custom-backend-in-nextauth-js-43k4

