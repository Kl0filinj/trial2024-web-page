<template>
    <div class="privacy-policy-container">
        <div class="privacy-policy-content">
            <h1>Privacy Policy</h1>
            <p>
                Privacy Policy

                Last updated: 11/27/2024
                We respect your privacy and are committed to protecting your personal information. This privacy policy
                explains how our app handles data provided by users.

                1. What data do we collect?
                We only collect data that you provide voluntarily when using our chatbot:

                Full name: to display your name in the chatbot.
                Age: to check if you meet age restrictions and provide a more appropriate chat experience.
                Location: to match chatbots in your city and country.
                Instagram profile ID: to identify and provide access to our service via Instagram.

                2. How do we use your data?
                We use the information you provide to us for the following purposes:

                Organizing communication with other users in your city and country.
                Supporting the operation of our chatbot and improving its functionality.
                Ensuring security and preventing unauthorized use of our application.

                3. How do we store your data?
                We take all reasonable measures to protect your data from loss, theft and unauthorized access. All data
                is stored in a secure database and transmitted over encrypted connections.

                4. Transfer of data to third parties
                We do not share your personal data with third parties except as required by law (e.g. at the request of
                law enforcement agencies).

                5. Your rights
                You have the right to:

                Request access to your data.
                To correct or delete your data.
                Restrict the processing of your data.
                Withdraw consent to data processing at any time by contacting us.

                6. Contact Information
                If you have any questions about our privacy policy or how we process your data, please contact us:

                Email: instfwinebot@gmail.com

                7. Changes to our privacy policy
                We may update this policy from time to time. Any changes will be posted on this page and we encourage
                you to check it periodically.

                By continuing to use our app, you acknowledge that you have read this privacy policy and agree to its
                terms.
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PrivacyPolicy'
}
</script>

<style scoped>
.privacy-policy-container {
    display: flex;
    justify-content: center;
    /* align-items: center; */
    min-height: 100vh;
    padding: 20px;
}

.privacy-policy-content {
    max-width: 800px;
    text-align: center;
}

h1 {
    margin-bottom: 20px;
}

p {
    margin-bottom: 15px;
}
</style>