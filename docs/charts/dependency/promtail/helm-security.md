# Helm Security

## Helm-Chart

##### Scan Results

#### Chart Object: app.yaml
    

      
| Type         |    Misconfiguration ID   |   Check  |  Severity |                   Explaination                   | Links  |
|:----------------|:------------------:|:-----------:|:------------------:|-----------------------------------------|-----------------------------------------|
| Rbac Security Check         |    KSV044   |   No wildcard verb and resource roles  |  CRITICAL | <details><summary>Expand...</summary> Check whether role permits wildcard verb on wildcard resource <br /> <hr /> <br /> Role permits wildcard verb on wildcard resource </details>| <details><summary>Expand...</summary><a href="https://kubernetes.io/docs/concepts/security/rbac-good-practices/">https://kubernetes.io/docs/concepts/security/rbac-good-practices/</a><br /><a href="https://avd.aquasec.com/misconfig/ksv044">https://avd.aquasec.com/misconfig/ksv044</a><br /></details>  |
| Rbac Security Check         |    KSV046   |   No wildcard resource roles  |  CRITICAL | <details><summary>Expand...</summary> Check whether role permits specific verb on wildcard resources <br /> <hr /> <br /> Role permits specific verb on wildcard resource </details>| <details><summary>Expand...</summary><a href="https://kubernetes.io/docs/concepts/security/rbac-good-practices/">https://kubernetes.io/docs/concepts/security/rbac-good-practices/</a><br /><a href="https://avd.aquasec.com/misconfig/ksv046">https://avd.aquasec.com/misconfig/ksv046</a><br /></details>  |
| Rbac Security Check         |    KSV047   |   Do not allow privilege escalation from node proxy  |  HIGH | <details><summary>Expand...</summary> Check whether role permits privilege escalation from node proxy <br /> <hr /> <br /> Role permits privilege escalation from node proxy </details>| <details><summary>Expand...</summary><a href="https://kubernetes.io/docs/concepts/security/rbac-good-practices/">https://kubernetes.io/docs/concepts/security/rbac-good-practices/</a><br /><a href="https://avd.aquasec.com/misconfig/ksv047">https://avd.aquasec.com/misconfig/ksv047</a><br /></details>  |