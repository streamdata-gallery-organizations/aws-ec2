---
name: AWS EC2
x-slug: aws-ec2
description: Amazon Elastic Compute Cloud is a web service that provides resizable
  compute capacity in the cloud. It is designed to make web-scale cloud computing
  easier for developers. Amazon EC2s simple web service interface allows you to obtain
  and configure capacity with minimal friction. It provides you with complete control
  of your computing resources and lets you run on Amazon&rsquo;s proven computing
  environment. Amazon EC2 reduces the time required to obtain and boot new server
  instances to minutes, allowing you to quickly scale capacity, both up and down,
  as your computing requirements change. Amazon EC2 changes the economics of computing
  by allowing you to pay only for capacity that you actually use. Amazon EC2 provides
  developers the tools to build failure resilient applications and isolate themselves
  from common failure scenarios.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS EC2
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API Describe Account Attributes
  x-api-slug: aws-ec2-api
  description: Describes attributes of your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeAccountAttributes
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeaccountattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeaccountattributes-get-openapi.md
- name: AWS EC2 API Copy Image
  x-api-slug: aws-ec2-api
  description: Initiates the copy of an AMI from the specified source region to the
    current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CopyImage
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncopyimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncopyimage-get-openapi.md
- name: AWS EC2 API Create Image
  x-api-slug: aws-ec2-api
  description: Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance
    that is either running or stopped.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateImage
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateimage-get-openapi.md
- name: AWS EC2 API Deregister Image
  x-api-slug: aws-ec2-api
  description: Deregisters the specified AMI.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeregisterImage
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionderegisterimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionderegisterimage-get-openapi.md
- name: AWS EC2 API Describe Image Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified AMI.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeImageAttribute
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimageattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimageattribute-get-openapi.md
- name: AWS EC2 API Describe Images
  x-api-slug: aws-ec2-api
  description: Describes one or more of the images (AMIs, AKIs, and ARIs) available
    to you.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeImages
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimages-get-openapi.md
- name: AWS EC2 API Modify Image Attribute
  x-api-slug: aws-ec2-api
  description: Modifies the specified attribute of the specified AMI.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyImageAttribute
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyimageattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyimageattribute-get-openapi.md
- name: AWS EC2 API Register Image
  x-api-slug: aws-ec2-api
  description: Registers an AMI.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RegisterImage
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionregisterimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionregisterimage-get-openapi.md
- name: AWS EC2 API Reset Image Attribute
  x-api-slug: aws-ec2-api
  description: Resets an attribute of an AMI to its default value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ResetImageAttribute
  tags: Server Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetimageattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetimageattribute-get-openapi.md
- name: AWS EC2 API Confirm Product Instance
  x-api-slug: aws-ec2-api
  description: Determines whether a product code is associated with an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ConfirmProductInstance
  tags: Product Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionconfirmproductinstance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionconfirmproductinstance-get-openapi.md
- name: AWS EC2 API Bundle Instance
  x-api-slug: aws-ec2-api
  description: Bundles an Amazon instance store-backed Windows instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=BundleInstance
  tags: Bundle Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionbundleinstance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionbundleinstance-get-openapi.md
- name: AWS EC2 API Cancel Bundle Task
  x-api-slug: aws-ec2-api
  description: Cancels a bundling operation for an instance store-backed Windows instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelBundleTask
  tags: Bundle Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelbundletask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelbundletask-get-openapi.md
- name: AWS EC2 API Describe Bundle Tasks
  x-api-slug: aws-ec2-api
  description: Describes one or more of your bundling tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeBundleTasks
  tags: Bundle Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribebundletasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribebundletasks-get-openapi.md
- name: AWS EC2 API Attach Classic Link Vpc
  x-api-slug: aws-ec2-api
  description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
    one or more of the VPC's\n\t\t\tsecurity groups."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachClassicLinkVpc
  tags: VPC Link
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API Describe Classic Link Instances
  x-api-slug: aws-ec2-api
  description: Describes one or more of your linked EC2-Classic instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeClassicLinkInstances
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeclassiclinkinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeclassiclinkinstances-get-openapi.md
- name: AWS EC2 API Describe Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Describes the ClassicLink status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-openapi.md
- name: AWS EC2 API Describe Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Describes the ClassicLink DNS support status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcClassicLinkDnsSupport
  tags: VPC DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Detach Classic Link Vpc
  x-api-slug: aws-ec2-api
  description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachClassicLinkVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API Disable Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Disables ClassicLink for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisableVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-openapi.md
- name: AWS EC2 API Disable Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Disables ClassicLink DNS support for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisableVpcClassicLinkDnsSupport
  tags: VPC DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Enable Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Enables a VPC for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevpcclassiclink-get-openapi.md
- name: AWS EC2 API Enable Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Enables a VPC to support DNS hostname resolution for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVpcClassicLinkDnsSupport
  tags: VPC NS
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Create Customer Gateway
  x-api-slug: aws-ec2-api
  description: Provides information to AWS about your VPN customer gateway device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateCustomerGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatecustomergateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatecustomergateway-get-openapi.md
- name: AWS EC2 API Delete Customer Gateway
  x-api-slug: aws-ec2-api
  description: Deletes the specified customer gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteCustomerGateway
  tags: Customer Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletecustomergateway-get-openapi.md
- name: AWS EC2 API Describe Customer Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPN customer gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeCustomerGateways
  tags: Customer Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribecustomergateways-get-openapi.md
- name: AWS EC2 API Allocate Hosts
  x-api-slug: aws-ec2-api
  description: Allocates a Dedicated Host to your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AllocateHosts
  tags: Host
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionallocatehosts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionallocatehosts-get-openapi.md
- name: AWS EC2 API Describe Hosts
  x-api-slug: aws-ec2-api
  description: Describes one or more of your Dedicated Hosts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeHosts
  tags: Hosts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribehosts-get-openapi.md
- name: AWS EC2 API Describe Host Reservation Offerings
  x-api-slug: aws-ec2-api
  description: Describes the Dedicated Host Reservations that are available to purchase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeHostReservationOfferings
  tags: Host Reservation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribehostreservationofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribehostreservationofferings-get-openapi.md
- name: AWS EC2 API Describe Host Reservations
  x-api-slug: aws-ec2-api
  description: |-
    Describes Dedicated Host Reservations which are associated with Dedicated Hosts in
                your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeHostReservations
  tags: Host Reservation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribehostreservations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribehostreservations-get-openapi.md
- name: AWS EC2 API Get Host Reservation Purchase Preview
  x-api-slug: aws-ec2-api
  description: |-
    Preview a reservation purchase with configurations that match those of your
                Dedicated Host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=GetHostReservationPurchasePreview
  tags: Host Reservation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongethostreservationpurchasepreview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongethostreservationpurchasepreview-get-openapi.md
- name: AWS EC2 API Modify Hosts
  x-api-slug: aws-ec2-api
  description: Modify the auto-placement setting of a Dedicated Host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyHosts
  tags: Hosts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyhosts-get-openapi.md
- name: AWS EC2 API Modify Instance Placement
  x-api-slug: aws-ec2-api
  description: |-
    Set the instance affinity value for a specific stopped instance and modify the
                instance tenancy setting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyInstancePlacement
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyinstanceplacement-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyinstanceplacement-get-openapi.md
- name: AWS EC2 API Purchase Host Reservation
  x-api-slug: aws-ec2-api
  description: Purchase a reservation with configurations that match those of your
    Dedicated Host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=PurchaseHostReservation
  tags: Host Reservation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasehostreservation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasehostreservation-get-openapi.md
- name: AWS EC2 API Release Hosts
  x-api-slug: aws-ec2-api
  description: When you no longer want to use an On-Demand Dedicated Host it can be
    released.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReleaseHosts
  tags: Hosts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreleasehosts-get-openapi.md
- name: AWS EC2 API Associate Dhcp Options
  x-api-slug: aws-ec2-api
  description: Associates a set of DHCP options (that you've previously created) with
    the specified VPC, or associates no DHCP options with the VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateDhcpOptions
  tags: DHCP
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatedhcpoptions-get-openapi.md
- name: AWS EC2 API Create Dhcp Options
  x-api-slug: aws-ec2-api
  description: Creates a set of DHCP options for your VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateDhcpOptions
  tags: DHCP
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatedhcpoptions-get-openapi.md
- name: AWS EC2 API Delete Dhcp Options
  x-api-slug: aws-ec2-api
  description: Deletes the specified set of DHCP options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteDhcpOptions
  tags: DHCP
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletedhcpoptions-get-openapi.md
- name: AWS EC2 API Describe Dhcp Options
  x-api-slug: aws-ec2-api
  description: Describes one or more of your DHCP options sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeDhcpOptions
  tags: DHCP
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribedhcpoptions-get-openapi.md
- name: AWS EC2 API Attach Volume
  x-api-slug: aws-ec2-api
  description: |-
    Attaches an EBS volume to a running or stopped instance and exposes it to the instance with
          the specified device name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachVolume
  tags: Drive Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachvolume-get-openapi.md
- name: AWS EC2 API Copy Snapshot
  x-api-slug: aws-ec2-api
  description: Copies a point-in-time snapshot of an EBS volume and stores it in Amazon
    S3.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CopySnapshot
  tags: Drive Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncopysnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncopysnapshot-get-openapi.md
- name: AWS EC2 API Create Snapshot
  x-api-slug: aws-ec2-api
  description: Creates a snapshot of an EBS volume and stores it in Amazon S3.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateSnapshot
  tags: Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatesnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatesnapshot-get-openapi.md
- name: AWS EC2 API Create Volume
  x-api-slug: aws-ec2-api
  description: Creates an EBS volume that can be attached to an instance in the same
    Availability Zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevolume-get-openapi.md
- name: AWS EC2 API Delete Snapshot
  x-api-slug: aws-ec2-api
  description: Deletes the specified snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteSnapshot
  tags: Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletesnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletesnapshot-get-openapi.md
- name: AWS EC2 API Delete Volume
  x-api-slug: aws-ec2-api
  description: Deletes the specified EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevolume-get-openapi.md
- name: AWS EC2 API Describe Snapshot Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSnapshotAttribute
  tags: Drive Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesnapshotattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesnapshotattribute-get-openapi.md
- name: AWS EC2 API Describe Snapshots
  x-api-slug: aws-ec2-api
  description: Describes one or more of the EBS snapshots available to you.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSnapshots
  tags: Drive Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesnapshots-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesnapshots-get-openapi.md
- name: AWS EC2 API Describe Volume Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumeAttribute
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevolumeattribute-get-openapi.md
- name: AWS EC2 API Describe Volumes
  x-api-slug: aws-ec2-api
  description: Describes the specified EBS volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumes
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevolumes-get-openapi.md
- name: AWS EC2 API Describe Volume Status
  x-api-slug: aws-ec2-api
  description: Describes the status of the specified volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumeStatus
  tags: Volume Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevolumestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevolumestatus-get-openapi.md
- name: AWS EC2 API Detach Volume
  x-api-slug: aws-ec2-api
  description: Detaches an EBS volume from an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachvolume-get-openapi.md
- name: AWS EC2 API Enable Volume I O
  x-api-slug: aws-ec2-api
  description: |-
    Enables I/O operations for a volume that had I/O operations disabled because the data on the
          volume was potentially inconsistent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVolumeIO
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevolumeio-get-openapi.md
- name: AWS EC2 API Modify Snapshot Attribute
  x-api-slug: aws-ec2-api
  description: Adds or removes permission settings for the specified snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifySnapshotAttribute
  tags: Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifysnapshotattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifysnapshotattribute-get-openapi.md
- name: AWS EC2 API Modify Volume Attribute
  x-api-slug: aws-ec2-api
  description: Modifies a volume attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVolumeAttribute
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvolumeattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvolumeattribute-get-openapi.md
- name: AWS EC2 API Reset Snapshot Attribute
  x-api-slug: aws-ec2-api
  description: Resets permission settings for the specified snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ResetSnapshotAttribute
  tags: Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetsnapshotattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetsnapshotattribute-get-openapi.md
- name: AWS EC2 API Allocate Address
  x-api-slug: aws-ec2-api
  description: Acquires an Elastic IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AllocateAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionallocateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionallocateaddress-get-openapi.md
- name: AWS EC2 API Associate Address
  x-api-slug: aws-ec2-api
  description: Associates an Elastic IP address with an instance or a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociateaddress-get-openapi.md
- name: AWS EC2 API Describe Addresses
  x-api-slug: aws-ec2-api
  description: Describes one or more of your Elastic IP addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeAddresses
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeaddresses-get-openapi.md
- name: AWS EC2 API Describe Moving Addresses
  x-api-slug: aws-ec2-api
  description: Describes your Elastic IP addresses that are being moved to the EC2-VPC
    platform, or that are being restored to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeMovingAddresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribemovingaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribemovingaddresses-get-openapi.md
- name: AWS EC2 API Disassociate Address
  x-api-slug: aws-ec2-api
  description: Disassociates an Elastic IP address from the instance or network interface
    it's associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisassociateAddress
  tags: IIP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociateaddress-get-openapi.md
- name: AWS EC2 API Move Address To Vpc
  x-api-slug: aws-ec2-api
  description: Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC
    platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=MoveAddressToVpc
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmoveaddresstovpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmoveaddresstovpc-get-openapi.md
- name: AWS EC2 API Release Address
  x-api-slug: aws-ec2-api
  description: Releases the specified Elastic IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReleaseAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreleaseaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreleaseaddress-get-openapi.md
- name: AWS EC2 API Restore Address To Classic
  x-api-slug: aws-ec2-api
  description: Restores an Elastic IP address that was previously moved to the EC2-VPC
    platform back to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RestoreAddressToClassic
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-openapi.md
- name: AWS EC2 API Assign Ipv6 Addresses
  x-api-slug: aws-ec2-api
  description: Assigns one or more IPv6 addresses to the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssignIpv6Addresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassignipv6addresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassignipv6addresses-get-openapi.md
- name: AWS EC2 API Assign Private Ip Addresses
  x-api-slug: aws-ec2-api
  description: Assigns one or more secondary private IP addresses to the specified
    network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssignPrivateIpAddresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassignprivateipaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassignprivateipaddresses-get-openapi.md
- name: AWS EC2 API Attach Network Interface
  x-api-slug: aws-ec2-api
  description: Attaches a network interface to an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachNetworkInterface
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachnetworkinterface-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachnetworkinterface-get-openapi.md
- name: AWS EC2 API Create Network Interface
  x-api-slug: aws-ec2-api
  description: Creates a network interface in the specified subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNetworkInterface
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkinterface-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkinterface-get-openapi.md
- name: AWS EC2 API Delete Network Interface
  x-api-slug: aws-ec2-api
  description: Deletes the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteNetworkInterface
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkinterface-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkinterface-get-openapi.md
- name: AWS EC2 API Describe Network Interface Attribute
  x-api-slug: aws-ec2-api
  description: Describes a network interface attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeNetworkInterfaceAttribute
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkinterfaceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkinterfaceattribute-get-openapi.md
- name: AWS EC2 API Describe Network Interfaces
  x-api-slug: aws-ec2-api
  description: Describes one or more of your network interfaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeNetworkInterfaces
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkinterfaces-get-openapi.md
- name: AWS EC2 API Detach Network Interface
  x-api-slug: aws-ec2-api
  description: Detaches a network interface from an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachNetworkInterface
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachnetworkinterface-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachnetworkinterface-get-openapi.md
- name: AWS EC2 API Modify Network Interface Attribute
  x-api-slug: aws-ec2-api
  description: Modifies the specified network interface attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyNetworkInterfaceAttribute
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifynetworkinterfaceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifynetworkinterfaceattribute-get-openapi.md
- name: AWS EC2 API Reset Network Interface Attribute
  x-api-slug: aws-ec2-api
  description: Resets a network interface attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ResetNetworkInterfaceAttribute
  tags: Network Interface
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetnetworkinterfaceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetnetworkinterfaceattribute-get-openapi.md
- name: AWS EC2 API Unassign Ipv6 Addresses
  x-api-slug: aws-ec2-api
  description: Unassigns one or more IPv6 addresses from a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=UnassignIpv6Addresses
  tags: IPv6 Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunassignipv6addresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunassignipv6addresses-get-openapi.md
- name: AWS EC2 API Unassign Private Ip Addresses
  x-api-slug: aws-ec2-api
  description: Unassigns one or more secondary private IP addresses from a network
    interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=UnassignPrivateIpAddresses
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunassignprivateipaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunassignprivateipaddresses-get-openapi.md
- name: AWS EC2 API Describe Instance Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeInstanceAttribute
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstanceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstanceattribute-get-openapi.md
- name: AWS EC2 API Describe Instances
  x-api-slug: aws-ec2-api
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeInstances
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstances-get-openapi.md
- name: AWS EC2 API Describe Instance Status
  x-api-slug: aws-ec2-api
  description: Describes the status of one or more instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeInstanceStatus
  tags: Server Instance Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstancestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinstancestatus-get-openapi.md
- name: AWS EC2 API Get Console Output
  x-api-slug: aws-ec2-api
  description: Gets the console output for the specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=GetConsoleOutput
  tags: Console Output
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetconsoleoutput-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetconsoleoutput-get-openapi.md
- name: AWS EC2 API Get Console Screenshot
  x-api-slug: aws-ec2-api
  description: Retrieve a JPG-format screenshot of a running instance to help with
    troubleshooting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=GetConsoleScreenshot
  tags: Console Screenshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetconsolescreenshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetconsolescreenshot-get-openapi.md
- name: AWS EC2 API Get Password Data
  x-api-slug: aws-ec2-api
  description: Retrieves the encrypted administrator password for an instance running
    Windows.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=GetPasswordData
  tags: Password Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetpassworddata-get-openapi.md
- name: AWS EC2 API Modify Instance Attribute
  x-api-slug: aws-ec2-api
  description: Modifies the specified attribute of the specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyInstanceAttribute
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyinstanceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyinstanceattribute-get-openapi.md
- name: AWS EC2 API Monitor Instances
  x-api-slug: aws-ec2-api
  description: Enables detailed monitoring for a running instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=MonitorInstances
  tags: Monitor Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmonitorinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmonitorinstances-get-openapi.md
- name: AWS EC2 API Reboot Instances
  x-api-slug: aws-ec2-api
  description: Requests a reboot of one or more instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RebootInstances
  tags: Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrebootinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrebootinstances-get-openapi.md
- name: AWS EC2 API Report Instance Status
  x-api-slug: aws-ec2-api
  description: Submits feedback about the status of an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReportInstanceStatus
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreportinstancestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreportinstancestatus-get-openapi.md
- name: AWS EC2 API Reset Instance Attribute
  x-api-slug: aws-ec2-api
  description: Resets an attribute of an instance to its default value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ResetInstanceAttribute
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetinstanceattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionresetinstanceattribute-get-openapi.md
- name: AWS EC2 API Run Instances
  x-api-slug: aws-ec2-api
  description: |-
    Launches the specified number of instances using an AMI for which you have
                permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RunInstances
  tags: Server Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionruninstances-get-openapi.md
- name: AWS EC2 API Start Instances
  x-api-slug: aws-ec2-api
  description: Starts an Amazon EBS-backed AMI that you've previously stopped.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=StartInstances
  tags: Server Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionstartinstances-get-openapi.md
- name: AWS EC2 API Stop Instances
  x-api-slug: aws-ec2-api
  description: Stops an Amazon EBS-backed instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=StopInstances
  tags: Server Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionstopinstances-get-openapi.md
- name: AWS EC2 API Terminate Instances
  x-api-slug: aws-ec2-api
  description: Shuts down one or more instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=TerminateInstances
  tags: Terminal Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionterminateinstances-get-openapi.md
- name: AWS EC2 API Unmonitor Instances
  x-api-slug: aws-ec2-api
  description: Disables detailed monitoring for a running instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=UnmonitorInstances
  tags: Server Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunmonitorinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionunmonitorinstances-get-openapi.md
- name: AWS EC2 API Attach Internet Gateway
  x-api-slug: aws-ec2-api
  description: "Attaches an Internet gateway to a VPC, enabling connectivity between
    the Internet\n\t\t\t\tand the VPC."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachinternetgateway-get-openapi.md
- name: AWS EC2 API Create Egress Only Internet Gateway
  x-api-slug: aws-ec2-api
  description: '[IPv6 only] Creates an egress-only Internet gateway for your VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateEgressOnlyInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateegressonlyinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateegressonlyinternetgateway-get-openapi.md
- name: AWS EC2 API Create Internet Gateway
  x-api-slug: aws-ec2-api
  description: Creates an Internet gateway for use with a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateinternetgateway-get-openapi.md
- name: AWS EC2 API Delete Egress Only Internet Gateway
  x-api-slug: aws-ec2-api
  description: Deletes an egress-only Internet gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteEgressOnlyInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteegressonlyinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteegressonlyinternetgateway-get-openapi.md
- name: AWS EC2 API Delete Internet Gateway
  x-api-slug: aws-ec2-api
  description: Deletes the specified Internet gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteinternetgateway-get-openapi.md
- name: AWS EC2 API Describe Egress Only Internet Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of your egress-only Internet gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeEgressOnlyInternetGateways
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeegressonlyinternetgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeegressonlyinternetgateways-get-openapi.md
- name: AWS EC2 API Describe Internet Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of your Internet gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeInternetGateways
  tags: Internet Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeinternetgateways-get-openapi.md
- name: AWS EC2 API Detach Internet Gateway
  x-api-slug: aws-ec2-api
  description: Detaches an Internet gateway from a VPC, disabling connectivity between
    the Internet and the VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachInternetGateway
  tags: Internet Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondetachinternetgateway-get-openapi.md
- name: AWS EC2 API Create Key Pair
  x-api-slug: aws-ec2-api
  description: Creates a 2048-bit RSA key pair with the specified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateKeyPair
  tags: Key Pair
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatekeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatekeypair-get-openapi.md
- name: AWS EC2 API Delete Key Pair
  x-api-slug: aws-ec2-api
  description: Deletes the specified key pair, by removing the public key from Amazon
    EC2.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteKeyPair
  tags: Key Pair
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletekeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletekeypair-get-openapi.md
- name: AWS EC2 API Describe Key Pairs
  x-api-slug: aws-ec2-api
  description: Describes one or more of your key pairs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeKeyPairs
  tags: Key Paris
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribekeypairs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribekeypairs-get-openapi.md
- name: AWS EC2 API Import Key Pair
  x-api-slug: aws-ec2-api
  description: Imports the public key from an RSA key pair that you created with a
    third-party tool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportKeyPair
  tags: Key Pair
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportkeypair-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportkeypair-get-openapi.md
- name: AWS EC2 API Create Nat Gateway
  x-api-slug: aws-ec2-api
  description: Creates a NAT gateway in the specified subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNatGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenatgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenatgateway-get-openapi.md
- name: AWS EC2 API Delete Nat Gateway
  x-api-slug: aws-ec2-api
  description: Deletes the specified NAT gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteNatGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenatgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenatgateway-get-openapi.md
- name: AWS EC2 API Describe Nat Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of the your NAT gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeNatGateways
  tags: NAT Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenatgateways-get-openapi.md
- name: AWS EC2 API Create Network Acl
  x-api-slug: aws-ec2-api
  description: Creates a network ACL in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNetworkAcl
  tags: VPC ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkacl-get-openapi.md
- name: AWS EC2 API Create Network Acl Entry
  x-api-slug: aws-ec2-api
  description: Creates an entry (a rule) in a network ACL with the specified rule
    number.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNetworkAclEntry
  tags: VPC ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkaclentry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatenetworkaclentry-get-openapi.md
- name: AWS EC2 API Delete Network Acl
  x-api-slug: aws-ec2-api
  description: Deletes the specified network ACL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteNetworkAcl
  tags: Network ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkacl-get-openapi.md
- name: AWS EC2 API Delete Network Acl Entry
  x-api-slug: aws-ec2-api
  description: Deletes the specified ingress or egress entry (rule) from the specified
    network ACL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteNetworkAclEntry
  tags: Network ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkaclentry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletenetworkaclentry-get-openapi.md
- name: AWS EC2 API Describe Network Acls
  x-api-slug: aws-ec2-api
  description: Describes one or more of your network ACLs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeNetworkAcls
  tags: Network ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkacls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribenetworkacls-get-openapi.md
- name: AWS EC2 API Replace Network Acl Association
  x-api-slug: aws-ec2-api
  description: Changes which network ACL a subnet is associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReplaceNetworkAclAssociation
  tags: Network ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplacenetworkaclassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplacenetworkaclassociation-get-openapi.md
- name: AWS EC2 API Replace Network Acl Entry
  x-api-slug: aws-ec2-api
  description: Replaces an entry (rule) in a network ACL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReplaceNetworkAclEntry
  tags: Network ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplacenetworkaclentry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplacenetworkaclentry-get-openapi.md
- name: AWS EC2 API Create Placement Group
  x-api-slug: aws-ec2-api
  description: Creates a placement group that you launch cluster instances into.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreatePlacementGroup
  tags: Placement Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateplacementgroup-get-openapi.md
- name: AWS EC2 API Delete Placement Group
  x-api-slug: aws-ec2-api
  description: Deletes the specified placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeletePlacementGroup
  tags: Placement Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteplacementgroup-get-openapi.md
- name: AWS EC2 API Describe Placement Groups
  x-api-slug: aws-ec2-api
  description: Describes one or more of your placement groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribePlacementGroups
  tags: Placement Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeplacementgroups-get-openapi.md
- name: AWS EC2 API Describe Availability Zones
  x-api-slug: aws-ec2-api
  description: Describes one or more of the Availability Zones that are available
    to you.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeAvailabilityZones
  tags: Availability Zones
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeavailabilityzones-get-openapi.md
- name: AWS EC2 API Describe Regions
  x-api-slug: aws-ec2-api
  description: Describes one or more regions that are currently available to you.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeRegions
  tags: Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescriberegions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescriberegions-get-openapi.md
- name: AWS EC2 API Accept Reserved Instances Exchange Quote
  x-api-slug: aws-ec2-api
  description: Accepts the Convertible Reserved Instance exchange quote described
    in the GetReservedInstancesExchangeQuote call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AcceptReservedInstancesExchangeQuote
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionacceptreservedinstancesexchangequote-get-openapi.md
- name: AWS EC2 API Cancel Reserved Instances Listing
  x-api-slug: aws-ec2-api
  description: Cancels the specified Reserved Instance listing in the Reserved Instance
    Marketplace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelReservedInstancesListing
  tags: Reserved Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelreservedinstanceslisting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelreservedinstanceslisting-get-openapi.md
- name: AWS EC2 API Create Reserved Instances Listing
  x-api-slug: aws-ec2-api
  description: "Creates a listing for Amazon EC2 Standard Reserved Instances to be
    sold in the Reserved Instance\n\t\t\tMarketplace."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateReservedInstancesListing
  tags: Reserved Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatereservedinstanceslisting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatereservedinstanceslisting-get-openapi.md
- name: AWS EC2 API Describe Reserved Instances
  x-api-slug: aws-ec2-api
  description: Describes one or more of the Reserved Instances that you purchased.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeReservedInstances
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribereservedinstances-get-openapi.md
- name: AWS EC2 API Describe Reserved Instances Listings
  x-api-slug: aws-ec2-api
  description: Describes your account's Reserved Instance listings in the Reserved
    Instance Marketplace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeReservedInstancesListings
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribereservedinstanceslistings-get-openapi.md
- name: AWS EC2 API Describe Reserved Instances Modifications
  x-api-slug: aws-ec2-api
  description: Describes the modifications made to your Reserved Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeReservedInstancesModifications
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribereservedinstancesmodifications-get-openapi.md
- name: AWS EC2 API Describe Reserved Instances Offerings
  x-api-slug: aws-ec2-api
  description: Describes Reserved Instance offerings that are available for purchase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeReservedInstancesOfferings
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribereservedinstancesofferings-get-openapi.md
- name: AWS EC2 API Get Reserved Instances Exchange Quote
  x-api-slug: aws-ec2-api
  description: Returns details about the values and term of your specified Convertible
    Reserved Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=GetReservedInstancesExchangeQuote
  tags: Reserved Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiongetreservedinstancesexchangequote-get-openapi.md
- name: AWS EC2 API Modify Reserved Instances
  x-api-slug: aws-ec2-api
  description: Modifies the Availability Zone, instance count, instance type, or network
    platform (EC2-Classic or EC2-VPC) of your Standard Reserved Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyReservedInstances
  tags: Reserved Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyreservedinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyreservedinstances-get-openapi.md
- name: AWS EC2 API Purchase Reserved Instances Offering
  x-api-slug: aws-ec2-api
  description: Purchases a Reserved Instance for use with your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=PurchaseReservedInstancesOffering
  tags: Reserved Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasereservedinstancesoffering-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasereservedinstancesoffering-get-openapi.md
- name: AWS EC2 API Describe Identity Id Format
  x-api-slug: aws-ec2-api
  description: |-
    Describes the ID format settings for resources for the specified IAM user, IAM role, or root
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeIdentityIdFormat
  tags: Identity Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeidentityidformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeidentityidformat-get-openapi.md
- name: AWS EC2 API Describe Id Format
  x-api-slug: aws-ec2-api
  description: Describes the ID format settings for your resources on a per-region
    basis, for example, to view which resource types are enabled for longer IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeIdFormat
  tags: Identity Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeidformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeidformat-get-openapi.md
- name: AWS EC2 API Modify Identity Id Format
  x-api-slug: aws-ec2-api
  description: |-
    Modifies the ID format of a resource for a specified IAM user, IAM role, or the root
          user for an account; or all IAM users, IAM roles, and the root user for an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyIdentityIdFormat
  tags: Identity Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyidentityidformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyidentityidformat-get-openapi.md
- name: AWS EC2 API Modify Id Format
  x-api-slug: aws-ec2-api
  description: Modifies the ID format for the specified resource on a per-region basis.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyIdFormat
  tags: Identity Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyidformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyidformat-get-openapi.md
- name: AWS EC2 API Associate Route Table
  x-api-slug: aws-ec2-api
  description: Associates a subnet with a route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateRouteTable
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociateroutetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociateroutetable-get-openapi.md
- name: AWS EC2 API Create Route
  x-api-slug: aws-ec2-api
  description: Creates a route in a route table within a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateRoute
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateroute-get-openapi.md
- name: AWS EC2 API Create Route Table
  x-api-slug: aws-ec2-api
  description: Creates a route table for the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateRouteTable
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateroutetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateroutetable-get-openapi.md
- name: AWS EC2 API Delete Route
  x-api-slug: aws-ec2-api
  description: Deletes the specified route from the specified route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteRoute
  tags: Route
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteroute-get-openapi.md
- name: AWS EC2 API Delete Route Table
  x-api-slug: aws-ec2-api
  description: Deletes the specified route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteRouteTable
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteroutetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteroutetable-get-openapi.md
- name: AWS EC2 API Describe Route Tables
  x-api-slug: aws-ec2-api
  description: Describes one or more of your route tables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeRouteTables
  tags: Route Tables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescriberoutetables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescriberoutetables-get-openapi.md
- name: AWS EC2 API Disable Vgw Route Propagation
  x-api-slug: aws-ec2-api
  description: Disables a virtual private gateway (VGW) from propagating routes to
    a specified route table of a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisableVgwRoutePropagation
  tags: Virtual Private Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisablevgwroutepropagation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisablevgwroutepropagation-get-openapi.md
- name: AWS EC2 API Disassociate Route Table
  x-api-slug: aws-ec2-api
  description: Disassociates a subnet from a route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisassociateRouteTable
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociateroutetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociateroutetable-get-openapi.md
- name: AWS EC2 API Enable Vgw Route Propagation
  x-api-slug: aws-ec2-api
  description: Enables a virtual private gateway (VGW) to propagate routes to the
    specified route table of a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVgwRoutePropagation
  tags: Virtual Private Gateway Route Propogation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevgwroutepropagation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionenablevgwroutepropagation-get-openapi.md
- name: AWS EC2 API Replace Route
  x-api-slug: aws-ec2-api
  description: Replaces an existing route within a route table in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReplaceRoute
  tags: Route
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplaceroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplaceroute-get-openapi.md
- name: AWS EC2 API Replace Route Table Association
  x-api-slug: aws-ec2-api
  description: Changes the route table associated with a given subnet in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReplaceRouteTableAssociation
  tags: Route Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplaceroutetableassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionreplaceroutetableassociation-get-openapi.md
- name: AWS EC2 API Describe Scheduled Instance Availability
  x-api-slug: aws-ec2-api
  description: Finds available schedules that meet the specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeScheduledInstanceAvailability
  tags: Server Instance Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribescheduledinstanceavailability-get-openapi.md
- name: AWS EC2 API Describe Scheduled Instances
  x-api-slug: aws-ec2-api
  description: Describes one or more of your Scheduled Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeScheduledInstances
  tags: Scheduled Server Instances
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribescheduledinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribescheduledinstances-get-openapi.md
- name: AWS EC2 API Purchase Scheduled Instances
  x-api-slug: aws-ec2-api
  description: Purchases one or more Scheduled Instances with the specified schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=PurchaseScheduledInstances
  tags: Scheduled Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasescheduledinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionpurchasescheduledinstances-get-openapi.md
- name: AWS EC2 API Run Scheduled Instances
  x-api-slug: aws-ec2-api
  description: Launches the specified Scheduled Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RunScheduledInstances
  tags: Scheduled Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrunscheduledinstances-get-openapi.md
- name: AWS EC2 API Authorize Security Group Egress ( E C2- V P C only)
  x-api-slug: aws-ec2-api
  description: '[EC2-VPC only] Adds one or more egress rules to a security group for
    use with a VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AuthorizeSecurityGroupEgress (EC2-VPC only)
  tags: Security Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionauthorizesecuritygroupegress-ec2vpc-only-get-openapi.md
- name: AWS EC2 API Authorize Security Group Ingress
  x-api-slug: aws-ec2-api
  description: Adds one or more ingress rules to a security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AuthorizeSecurityGroupIngress
  tags: Security Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionauthorizesecuritygroupingress-get-openapi.md
- name: AWS EC2 API Create Security Group
  x-api-slug: aws-ec2-api
  description: Creates a security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateSecurityGroup
  tags: Security Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatesecuritygroup-get-openapi.md
- name: AWS EC2 API Delete Security Group
  x-api-slug: aws-ec2-api
  description: Deletes a security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteSecurityGroup
  tags: Security  Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletesecuritygroup-get-openapi.md
- name: AWS EC2 API Describe Security Group References ( E C2- V P C only)
  x-api-slug: aws-ec2-api
  description: '[EC2-VPC only] Describes the VPCs on the other side of a VPC peering
    connection that are referencing the security groups you''ve specified in this
    request.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSecurityGroupReferences (EC2-VPC only)
  tags: Security Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesecuritygroupreferences-ec2vpc-only-get-openapi.md
- name: AWS EC2 API Describe Security Groups
  x-api-slug: aws-ec2-api
  description: Describes one or more of your security groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSecurityGroups
  tags: Security Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesecuritygroups-get-openapi.md
- name: AWS EC2 API Describe Stale Security Groups ( E C2- V P C only)
  x-api-slug: aws-ec2-api
  description: '[EC2-VPC only] Describes the stale security group rules for security
    groups in a specified VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeStaleSecurityGroups (EC2-VPC only)
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribestalesecuritygroups-ec2vpc-only-get-openapi.md
- name: AWS EC2 API Revoke Security Group Egress ( E C2- V P C only)
  x-api-slug: aws-ec2-api
  description: '[EC2-VPC only] Removes one or more egress rules from a security group
    for EC2-VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RevokeSecurityGroupEgress (EC2-VPC only)
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrevokesecuritygroupegress-ec2vpc-only-get-openapi.md
- name: AWS EC2 API Revoke Security Group Ingress
  x-api-slug: aws-ec2-api
  description: Removes one or more ingress rules from a security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RevokeSecurityGroupIngress
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrevokesecuritygroupingress-get-openapi.md
- name: AWS EC2 API Cancel Spot Instance Requests
  x-api-slug: aws-ec2-api
  description: Cancels one or more Spot instance requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelSpotInstanceRequests
  tags: Spot Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelspotinstancerequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelspotinstancerequests-get-openapi.md
- name: AWS EC2 API Create Spot Datafeed Subscription
  x-api-slug: aws-ec2-api
  description: Creates a data feed for Spot instances, enabling you to view Spot instance
    usage logs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateSpotDatafeedSubscription
  tags: Subnet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatespotdatafeedsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatespotdatafeedsubscription-get-openapi.md
- name: AWS EC2 API Delete Spot Datafeed Subscription
  x-api-slug: aws-ec2-api
  description: Deletes the data feed for Spot instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteSpotDatafeedSubscription
  tags: Spot Data Feed Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletespotdatafeedsubscription-get-openapi.md
- name: AWS EC2 API Describe Spot Datafeed Subscription
  x-api-slug: aws-ec2-api
  description: Describes the data feed for Spot instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotDatafeedSubscription
  tags: Spot Data Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotdatafeedsubscription-get-openapi.md
- name: AWS EC2 API Describe Spot Instance Requests
  x-api-slug: aws-ec2-api
  description: Describes the Spot instance requests that belong to your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotInstanceRequests
  tags: Spot Instance Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotinstancerequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotinstancerequests-get-openapi.md
- name: AWS EC2 API Describe Spot Price History
  x-api-slug: aws-ec2-api
  description: Describes the Spot price history.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotPriceHistory
  tags: Spot Price History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotpricehistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotpricehistory-get-openapi.md
- name: AWS EC2 API Request Spot Instances
  x-api-slug: aws-ec2-api
  description: Creates a Spot instance request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RequestSpotInstances
  tags: Spot Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrequestspotinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrequestspotinstances-get-openapi.md
- name: AWS EC2 API Cancel Spot Fleet Requests
  x-api-slug: aws-ec2-api
  description: Cancels the specified Spot fleet requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelSpotFleetRequests
  tags: Spot Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelspotfleetrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelspotfleetrequests-get-openapi.md
- name: AWS EC2 API Describe Spot Fleet Instances
  x-api-slug: aws-ec2-api
  description: Describes the running instances for the specified Spot fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotFleetInstances
  tags: Spot Fleet Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetinstances-get-openapi.md
- name: AWS EC2 API Describe Spot Fleet Request History
  x-api-slug: aws-ec2-api
  description: Describes the events for the specified Spot fleet request during the
    specified time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotFleetRequestHistory
  tags: Spot Fleet Request History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetrequesthistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetrequesthistory-get-openapi.md
- name: AWS EC2 API Describe Spot Fleet Requests
  x-api-slug: aws-ec2-api
  description: Describes your Spot fleet requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSpotFleetRequests
  tags: Sport Fleet Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribespotfleetrequests-get-openapi.md
- name: AWS EC2 API Modify Spot Fleet Request
  x-api-slug: aws-ec2-api
  description: Modifies the specified Spot fleet request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifySpotFleetRequest
  tags: Spot Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyspotfleetrequest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyspotfleetrequest-get-openapi.md
- name: AWS EC2 API Request Spot Fleet
  x-api-slug: aws-ec2-api
  description: Creates a Spot fleet request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RequestSpotFleet
  tags: Spot Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrequestspotfleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrequestspotfleet-get-openapi.md
- name: AWS EC2 API Associate Subnet Cidr Block
  x-api-slug: aws-ec2-api
  description: Associates a CIDR block with your subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateSubnetCidrBlock
  tags: CIDR Block
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatesubnetcidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatesubnetcidrblock-get-openapi.md
- name: AWS EC2 API Create Subnet
  x-api-slug: aws-ec2-api
  description: Creates a subnet in an existing VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateSubnet
  tags: Subnet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatesubnet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatesubnet-get-openapi.md
- name: AWS EC2 API Delete Subnet
  x-api-slug: aws-ec2-api
  description: Deletes the specified subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteSubnet
  tags: Subnet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletesubnet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletesubnet-get-openapi.md
- name: AWS EC2 API Describe Subnets
  x-api-slug: aws-ec2-api
  description: Describes one or more of your subnets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeSubnets
  tags: Subnets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesubnets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribesubnets-get-openapi.md
- name: AWS EC2 API Disassociate Subnet Cidr Block
  x-api-slug: aws-ec2-api
  description: Disassociates a CIDR block from a subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisassociateSubnetCidrBlock
  tags: CIDR Block
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociatesubnetcidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociatesubnetcidrblock-get-openapi.md
- name: AWS EC2 API Modify Subnet Attribute
  x-api-slug: aws-ec2-api
  description: Modifies a subnet attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifySubnetAttribute
  tags: Subnet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifysubnetattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifysubnetattribute-get-openapi.md
- name: AWS EC2 API Create Tags
  x-api-slug: aws-ec2-api
  description: |-
    Adds or overwrites one or more tags for the specified Amazon EC2 resource or
             resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatetags-get-openapi.md
- name: AWS EC2 API Delete Tags
  x-api-slug: aws-ec2-api
  description: Deletes the specified set of tags from the specified set of resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletetags-get-openapi.md
- name: AWS EC2 API Describe Tags
  x-api-slug: aws-ec2-api
  description: Describes one or more of the tags for your EC2 resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribetags-get-openapi.md
- name: AWS EC2 API Cancel Conversion Task
  x-api-slug: aws-ec2-api
  description: Cancels an active conversion task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelConversionTask
  tags: Bundle Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelconversiontask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelconversiontask-get-openapi.md
- name: AWS EC2 API Cancel Import Task
  x-api-slug: aws-ec2-api
  description: Cancels an in-process import virtual machine or import snapshot task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelImportTask
  tags: Import Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelimporttask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelimporttask-get-openapi.md
- name: AWS EC2 API Describe Conversion Tasks
  x-api-slug: aws-ec2-api
  description: Describes one or more of your conversion tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeConversionTasks
  tags: Version Tasks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeconversiontasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeconversiontasks-get-openapi.md
- name: AWS EC2 API Describe Import Image Tasks
  x-api-slug: aws-ec2-api
  description: Displays details about an import virtual machine or import snapshot
    tasks that are already created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeImportImageTasks
  tags: Import Image Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimportimagetasks-get-openapi.md
- name: AWS EC2 API Describe Import Snapshot Tasks
  x-api-slug: aws-ec2-api
  description: Describes your import snapshot tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeImportSnapshotTasks
  tags: Import Snapshot Takss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimportsnapshottasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeimportsnapshottasks-get-openapi.md
- name: AWS EC2 API Import Instance
  x-api-slug: aws-ec2-api
  description: Creates an import instance task using metadata from the specified disk
    image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportInstance
  tags: Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportinstance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportinstance-get-openapi.md
- name: AWS EC2 API Import Image
  x-api-slug: aws-ec2-api
  description: Displays details about an import virtual machine or import snapshot
    tasks that are already created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportImage
  tags: Import Image
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportimage-get-openapi.md
- name: AWS EC2 API Import Snapshot
  x-api-slug: aws-ec2-api
  description: Describes your import snapshot tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportSnapshot
  tags: Snapshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportsnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportsnapshot-get-openapi.md
- name: AWS EC2 API Import Volume
  x-api-slug: aws-ec2-api
  description: Creates an import volume task using metadata from the specified disk
    image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionimportvolume-get-openapi.md
- name: AWS EC2 API Cancel Export Task
  x-api-slug: aws-ec2-api
  description: Cancels an active export task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CancelExportTask
  tags: Export Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelexporttask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncancelexporttask-get-openapi.md
- name: AWS EC2 API Create Instance Export Task
  x-api-slug: aws-ec2-api
  description: Exports a running or stopped instance to an S3 bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateInstanceExportTask
  tags: Export Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateinstanceexporttask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateinstanceexporttask-get-openapi.md
- name: AWS EC2 API Describe Export Tasks
  x-api-slug: aws-ec2-api
  description: Describes one or more of your export tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeExportTasks
  tags: Export Takss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeexporttasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeexporttasks-get-openapi.md
- name: AWS EC2 API Associate Vpc Cidr Block
  x-api-slug: aws-ec2-api
  description: Associates a CIDR block with your VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateVpcCidrBlock
  tags: CIDR Block
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatevpccidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionassociatevpccidrblock-get-openapi.md
- name: AWS EC2 API Create Vpc
  x-api-slug: aws-ec2-api
  description: Creates a VPC with the specified IPv4 CIDR block.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpc-get-openapi.md
- name: AWS EC2 API Delete Vpc
  x-api-slug: aws-ec2-api
  description: Deletes the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpc-get-openapi.md
- name: AWS EC2 API Describe Vpc Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcAttribute
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcattribute-get-openapi.md
- name: AWS EC2 API Describe Vpcs
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcs
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcs-get-openapi.md
- name: AWS EC2 API Disassociate Vpc Cidr Block
  x-api-slug: aws-ec2-api
  description: Disassociates a CIDR block from a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisassociateVpcCidrBlock
  tags: CIDR Block
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociatevpccidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondisassociatevpccidrblock-get-openapi.md
- name: AWS EC2 API Modify Vpc Attribute
  x-api-slug: aws-ec2-api
  description: Modifies the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcAttribute
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcattribute-get-openapi.md
- name: AWS EC2 API Create Flow Logs
  x-api-slug: aws-ec2-api
  description: Creates one or more flow logs to capture IP traffic for a specific
    network interface, subnet, or VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateFlowLogs
  tags: Flow Logs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateflowlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreateflowlogs-get-openapi.md
- name: AWS EC2 API Delete Flow Logs
  x-api-slug: aws-ec2-api
  description: Deletes one or more flow logs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteFlowLogs
  tags: FLow Logs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteflowlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeleteflowlogs-get-openapi.md
- name: AWS EC2 API Describe Flow Logs
  x-api-slug: aws-ec2-api
  description: Describes one or more flow logs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeFlowLogs
  tags: Flow Logs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeflowlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeflowlogs-get-openapi.md
- name: AWS EC2 API Create Vpc Endpoint
  x-api-slug: aws-ec2-api
  description: Creates a VPC endpoint for a specified AWS service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpcEndpoint
  tags: VPC Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpcendpoint-get-openapi.md
- name: AWS EC2 API Delete Vpc Endpoints
  x-api-slug: aws-ec2-api
  description: Deletes one or more specified VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpcEndpoints
  tags: VPC Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpcendpoints-get-openapi.md
- name: AWS EC2 API Describe Prefix Lists
  x-api-slug: aws-ec2-api
  description: Describes available AWS services in a prefix list format, which includes
    the prefix list name and prefix list ID of the service and the IP address range
    for the service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribePrefixLists
  tags: Prefix List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeprefixlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribeprefixlists-get-openapi.md
- name: AWS EC2 API Describe Vpc Endpoints
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcEndpoints
  tags: VPC Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcendpoints-get-openapi.md
- name: AWS EC2 API Describe Vpc Endpoint Services
  x-api-slug: aws-ec2-api
  description: Describes all supported AWS services that can be specified when creating
    a VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcEndpointServices
  tags: VPC Endpoint Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcendpointservices-get-openapi.md
- name: AWS EC2 API Modify Vpc Endpoint
  x-api-slug: aws-ec2-api
  description: Modifies attributes of a specified VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcEndpoint
  tags: VPC Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-openapi.md
- name: AWS EC2 API Accept Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Accept a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AcceptVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Create Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: 'Requests a VPC peering connection between two VPCs: a requester VPC
    that you own and a peer VPC with which to create the connection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Delete Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Deletes a VPC peering connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Describe Vpc Peering Connections
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPC peering connections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcPeeringConnections
  tags: VPC Peering Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpcpeeringconnections-get-openapi.md
- name: AWS EC2 API Modify Vpc Peering Connection Options
  x-api-slug: aws-ec2-api
  description: Modifies the VPC peering connection options on one side of a VPC peering
    connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcPeeringConnectionOptions
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-openapi.md
- name: AWS EC2 API Reject Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Rejects a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RejectVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Create Vpn Connection
  x-api-slug: aws-ec2-api
  description: |-
    Creates a VPN connection between an existing virtual private gateway and a VPN customer
                gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpnConnection
  tags: VPC Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpnconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpnconnection-get-openapi.md
- name: AWS EC2 API Create Vpn Connection Route
  x-api-slug: aws-ec2-api
  description: Creates a static route associated with a VPN connection between an
    existing virtual private gateway and a VPN customer gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpnConnectionRoute
  tags: VPC Connection Route
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpnconnectionroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpnconnectionroute-get-openapi.md
- name: AWS EC2 API Delete Vpn Connection
  x-api-slug: aws-ec2-api
  description: Deletes the specified VPN connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpnConnection
  tags: VPN Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpnconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpnconnection-get-openapi.md
- name: AWS EC2 API Delete Vpn Connection Route
  x-api-slug: aws-ec2-api
  description: Deletes the specified static route associated with a VPN connection
    between an existing virtual private gateway and a VPN customer gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpnConnectionRoute
  tags: VPN Connection Route
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpnconnectionroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpnconnectionroute-get-openapi.md
- name: AWS EC2 API Describe Vpn Connections
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPN connections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpnConnections
  tags: VPN Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpnconnections-get-openapi.md
- name: AWS EC2 API Attach Vpn Gateway
  x-api-slug: aws-ec2-api
  description: Attaches a virtual private gateway to a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachVpnGateway
  tags: VPN Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachvpngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actionattachvpngateway-get-openapi.md
- name: AWS EC2 API Create Vpn Gateway
  x-api-slug: aws-ec2-api
  description: Creates a virtual private gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpnGateway
  tags: VPN Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actioncreatevpngateway-get-openapi.md
- name: AWS EC2 API Delete Vpn Gateway
  x-api-slug: aws-ec2-api
  description: Deletes the specified virtual private gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpnGateway
  tags: VPN Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondeletevpngateway-get-openapi.md
- name: AWS EC2 API Describe Vpn Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of your virtual private gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpnGateways
  tags: VPN Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/actiondescribevpngateways-get-openapi.md
- name: AWS EC2 API
  x-api-slug: aws-ec2-api
  description: Amazon Elastic Compute Cloud is a web service that provides resizable
    compute capacity in the cloud. It is designed to make web-scale cloud computing
    easier for developers. Amazon EC2s simple web service interface allows you to
    obtain and configure capacity with minimal friction. It provides you with complete
    control of your computing resources and lets you run on Amazon&rsquo;s proven
    computing environment. Amazon EC2 reduces the time required to obtain and boot
    new server instances to minutes, allowing you to quickly scale capacity, both
    up and down, as your computing requirements change. Amazon EC2 changes the economics
    of computing by allowing you to pay only for capacity that you actually use. Amazon
    EC2 provides developers the tools to build failure resilient applications and
    isolate themselves from common failure scenarios.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: AWS EC2
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2/master/_listings/aws-ec2/openapi.md
x-common:
- type: x-code
  url: http://aws.amazon.com/code/Amazon-EC2/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ec2/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ec2/pricing/
- type: x-sla
  url: https://aws.amazon.com/ec2/sla/
- type: x-website
  url: https://aws.amazon.com/ec2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---