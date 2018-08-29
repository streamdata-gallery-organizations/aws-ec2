{
  "info": {
    "name": "AWS EC2 API Get Console Output",
    "_postman_id": "f7b1ba31-0085-44b8-a444-c2ff7c027933",
    "description": "Gets the console output for the specified instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "a5a32612-ea00-4496-8081-404af86686ea",
          "name": "describeaccountattributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountAttributes?ClientToken=ClientToken&Description=Description&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&Name=Name&SourceImageId=SourceImageId&SourceRegion=SourceRegion",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes attributes of your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f40dad0-6adc-4dd0-8997-8ec2d68cb403"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "500ef472-04a4-4289-801c-95fbc3cad5e2",
          "name": "copyimage",
          "request": {
            "url": "http://example.com/api/?Action=CopyImage?BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&InstanceId=InstanceId&Name=Name&NoReboot=NoReboot",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the copy of an AMI from the specified source region to the current region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42f71830-c3c0-491f-a73f-43299626a887"
            }
          ]
        },
        {
          "id": "1c8a049e-6771-43ca-acb7-ab92d8cdcafc",
          "name": "createimage",
          "request": {
            "url": "http://example.com/api/?Action=CreateImage?DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is either running or stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b5c29d8-89ac-4121-bec3-7200f33b6f37"
            }
          ]
        },
        {
          "id": "54ea3731-8139-4a50-bd40-689353a7f3c7",
          "name": "deregisterimage",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f0a0e02-77cb-48f9-bed9-b0a5732c5a53"
            }
          ]
        },
        {
          "id": "0a22740c-347f-44f2-a4f4-6169724aa5d3",
          "name": "describeimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImageAttribute?DryRun=DryRun&ExecutableBy.N=ExecutableBy.N&Filter.N=Filter.N&ImageId.N=ImageId.N&Owner.N=Owner.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87b62feb-ec25-4fb1-8ea5-8cb9918f63c3"
            }
          ]
        },
        {
          "id": "7696bfa5-8656-40c9-a376-3078100de024",
          "name": "describeimages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Attribute=Attribute&Description=Description&DryRun=DryRun&ImageId=ImageId&LaunchPermission=LaunchPermission&OperationType=OperationType&ProductCode.N=ProductCode.N&UserGroup.N=UserGroup.N&UserId.N=UserId.N&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the images (AMIs, AKIs, and ARIs) available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4740ac32-c7b9-40ad-a76b-07e2649c5f5d"
            }
          ]
        },
        {
          "id": "4afaf597-73f1-4401-99c0-e1b30db882af",
          "name": "modifyimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyImageAttribute?Architecture=Architecture&BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&EnaSupport=EnaSupport&ImageLocation=ImageLocation&KernelId=KernelId&Name=Name&RamdiskId=RamdiskId&RootDeviceName=RootDeviceName&SriovNetSupport=SriovNetSupport&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30f0a84f-34a5-4032-847a-4ba07b2badf2"
            }
          ]
        },
        {
          "id": "d9af0099-a545-4caf-a4a4-2e540f1511ce",
          "name": "registerimage",
          "request": {
            "url": "http://example.com/api/?Action=RegisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a1fbe8f-12e9-447c-9a02-65e9c2cc162d"
            }
          ]
        },
        {
          "id": "ab6313cb-2029-45a7-bfe1-e2e98eb5e472",
          "name": "resetimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetImageAttribute?DryRun=DryRun&InstanceId=InstanceId&ProductCode=ProductCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an AMI to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "124fc98a-c7a7-409b-be19-abd7f546e358"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "00fa1887-20d0-4b5e-bf73-6bcfb3fc0e1a",
          "name": "confirmproductinstance",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmProductInstance?DryRun=DryRun&InstanceId=InstanceId&Storage=Storage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Determines whether a product code is associated with an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9cd4f6f-5bec-4685-a506-28905fdd5a1d"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "ad050089-1556-49c7-9275-1fd3061890df",
          "name": "bundleinstance",
          "request": {
            "url": "http://example.com/api/?Action=BundleInstance?BundleId=BundleId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Bundles an Amazon instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a36d2304-975c-4db6-a364-858de0063409"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "250ac750-ca87-47f5-9c6d-450348106a99",
          "name": "cancelbundletask",
          "request": {
            "url": "http://example.com/api/?Action=CancelBundleTask?BundleId.N=BundleId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a bundling operation for an instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "362d89fd-938e-4747-8e69-3795b737e85a"
            }
          ]
        },
        {
          "id": "cdc8a72a-07f4-4024-af3b-6f7112a5c38f",
          "name": "describebundletasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBundleTasks?DryRun=DryRun&InstanceId=InstanceId&SecurityGroupId.N=SecurityGroupId.N&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your bundling tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b08e17b1-7e81-42fe-8a9a-91ad8b89a44a"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "50e66734-933b-44d8-afd9-5d04474a4082",
          "name": "attachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=AttachClassicLinkVpc?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more of the VPC's\n\t\t\tsecurity groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38658030-e900-416e-a29d-534b630c772e"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "a4137f45-9fbd-4856-b8d4-ca2bc6633ac2",
          "name": "describeclassiclinkinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeClassicLinkInstances?DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your linked EC2-Classic instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d008d613-6395-4d87-8c36-449195493c77"
            }
          ]
        },
        {
          "id": "3cfc87b5-cbe2-40bb-b135-9a7c60f60f7b",
          "name": "modifyinstanceplacement",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstancePlacement?ClientToken=ClientToken&CurrencyCode=CurrencyCode&HostIdSet.N=HostIdSet.N&LimitPrice=LimitPrice&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set the instance affinity value for a specific stopped instance and modify the\n            instance tenancy setting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bdd164c0-db51-438c-94b1-958755cfc709"
            }
          ]
        },
        {
          "id": "b0c23c75-0913-4fce-9a58-8f4921b84cf0",
          "name": "describeinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceAttribute?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07c6be43-8d86-4b62-95d9-aa3af807501f"
            }
          ]
        },
        {
          "id": "22ebbb8d-b624-41f6-9696-948e89ccaf83",
          "name": "describeinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?DryRun=DryRun&Filter.N=Filter.N&IncludeAllInstances=IncludeAllInstances&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db4485c3-cc03-49de-a373-d682ad66f8f7"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "53ddd337-89cb-482f-8a7a-a29bfa036b80",
          "name": "describevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLink?MaxResults=MaxResults&NextToken=NextToken&VpcIds.N=VpcIds.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0365efc6-3621-4c8f-8296-31af44f376c1"
            }
          ]
        },
        {
          "id": "3ecb4f1c-996f-45a2-b20a-d4c99e5c6674",
          "name": "detachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=DetachClassicLinkVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks (detaches) a linked EC2-Classic instance from a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eaa42e53-05f3-4bfb-8941-be675ca061fa"
            }
          ]
        },
        {
          "id": "bc23548b-7864-4c7a-9a78-212cbc2d63ae",
          "name": "disablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f74b89e7-8083-4280-978d-6ba74b1fc551"
            }
          ]
        },
        {
          "id": "1ed9bf06-5fc9-4e77-9ea9-4df2333541d7",
          "name": "enablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f70a033d-d9e6-402e-9912-40bebc54d01c"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "87a6833c-5abb-4a54-876e-c4b3403b497d",
          "name": "describevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLinkDnsSupport?DryRun=DryRun&InstanceId=InstanceId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink DNS support status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8bd19abd-7694-43fd-a4ed-46406fb46633"
            }
          ]
        },
        {
          "id": "e106cdbf-3399-423b-9a8f-2d9d10591805",
          "name": "disablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLinkDnsSupport?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink DNS support for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5160b49a-faea-4389-b6db-68cd535abaf9"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "817464dd-a6e3-40b2-a639-c1f02ccbba5e",
          "name": "enablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLinkDnsSupport?BgpAsn=BgpAsn&DryRun=DryRun&IpAddress=IpAddress&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC to support DNS hostname resolution for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfa41286-2d84-42a9-a2a7-63a1a2437801"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "79bc799f-940d-485e-a065-c8df9672941f",
          "name": "createcustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateCustomerGateway?CustomerGatewayId=CustomerGatewayId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information to AWS about your VPN customer gateway device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "514dd6cb-aa16-4eb8-9164-5b3bb896dafd"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "30b315ca-4c9b-433b-a7d1-c9c3fce5acfb",
          "name": "deletecustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCustomerGateway?CustomerGatewayId.N=CustomerGatewayId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified customer gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "501c4005-e783-4299-a909-a460f21ee058"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "2fcc8cb9-d288-479a-9160-da2d999ab2cd",
          "name": "describecustomergateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCustomerGateways?AutoPlacement=AutoPlacement&AvailabilityZone=AvailabilityZone&ClientToken=ClientToken&InstanceType=InstanceType&Quantity=Quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPN customer gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8738d378-9a46-47cb-9dbe-fe34d56a8ff9"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "6c1db89e-5507-4488-94fb-1d1a442add3c",
          "name": "allocatehosts",
          "request": {
            "url": "http://example.com/api/?Action=AllocateHosts?Filter.N=Filter.N&HostId.N=HostId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allocates a Dedicated Host to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46e5b299-0a4d-468a-88da-a8bbdf8cf321"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "c0030b89-8d37-434a-ade6-43ecd428fcf9",
          "name": "describehosts",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHosts?Filter.N=Filter.N&MaxDuration=MaxDuration&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Dedicated Hosts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d788e0e-8dc1-41e0-a43f-9d2caa18a53d"
            }
          ]
        },
        {
          "id": "8b4b0349-e9d0-4ca7-b4d3-3189e4edf078",
          "name": "modifyhosts",
          "request": {
            "url": "http://example.com/api/?Action=ModifyHosts?Affinity=Affinity&HostId=HostId&InstanceId=InstanceId&Tenancy=Tenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modify the auto-placement setting of a Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ee80ffd-95db-4bf9-ab1e-b1c0f66de245"
            }
          ]
        },
        {
          "id": "2d1a6404-3928-4b2b-9950-159180cf81ef",
          "name": "releasehosts",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseHosts?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "When you no longer want to use an On-Demand Dedicated Host it can be released."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84138dcf-6b0d-4de5-bb33-d45524d8d71c"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "3d9b1858-0149-49ca-87ee-ef5e6cb0cdc6",
          "name": "describehostreservationofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservationOfferings?Filter.N=Filter.N&HostReservationIdSet.N=HostReservationIdSet.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Dedicated Host Reservations that are available to purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a0bbbc5-277a-4f77-a81a-66ea710c84b1"
            }
          ]
        },
        {
          "id": "a806ec11-4ab8-4722-8324-e00589a8c84e",
          "name": "describehostreservations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservations?HostIdSet.N=HostIdSet.N&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Dedicated Host Reservations which are associated with Dedicated Hosts in\n            your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78e60fa9-039a-48c5-ab29-10c15debd1b5"
            }
          ]
        },
        {
          "id": "1b9cec62-6999-4ce6-8af5-416aae3fae92",
          "name": "gethostreservationpurchasepreview",
          "request": {
            "url": "http://example.com/api/?Action=GetHostReservationPurchasePreview?AutoPlacement=AutoPlacement&HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Preview a reservation purchase with configurations that match those of your\n            Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f801e61e-6e06-4485-a81b-ea2a3d93a704"
            }
          ]
        },
        {
          "id": "5f0fd9ce-87eb-4c28-941f-9221253673aa",
          "name": "purchasehostreservation",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseHostReservation?HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchase a reservation with configurations that match those of your Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d5dfcd3-1425-4c2b-a358-101f890c9e72"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "d113faac-714a-4a21-8b9c-6e887fac4095",
          "name": "associatedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=AssociateDhcpOptions?DhcpConfiguration.N=DhcpConfiguration.N&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a set of DHCP options (that you've previously created) with the specified VPC, or associates no DHCP options with the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec6c4baf-c243-4dab-8f01-2ccda783750e"
            }
          ]
        },
        {
          "id": "7f766a6c-c8e4-45b8-b83c-f45bffc35145",
          "name": "createdhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=CreateDhcpOptions?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a set of DHCP options for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6101fcbc-3656-43c7-9806-5dcebde11b3c"
            }
          ]
        },
        {
          "id": "fe9b6a1e-df8a-4ef4-87f6-4a9a83a5612e",
          "name": "deletedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDhcpOptions?DhcpOptionsId.N=DhcpOptionsId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified set of DHCP options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa636ad5-5a66-4cd5-b82e-72937ca30d38"
            }
          ]
        },
        {
          "id": "de94cd1c-eea6-44c8-b0b4-1284cb8ad35c",
          "name": "describedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDhcpOptions?Device=Device&DryRun=DryRun&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your DHCP options sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d222d22e-84e5-4395-ae48-5caf9e22b6c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "cb8a1c6d-efcf-4019-86c3-ad5f6062802c",
          "name": "attachvolume",
          "request": {
            "url": "http://example.com/api/?Action=AttachVolume?Description=Description&DestinationRegion=DestinationRegion&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&PresignedUrl=PresignedUrl&SourceRegion=SourceRegion&SourceSnapshotId=SourceSnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an EBS volume to a running or stopped instance and exposes it to the instance with\n      the specified device name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "218144a9-f20a-40ae-9e1b-d3ca139f1cbf"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "5315367b-7bb4-4c7f-a129-8ceef79fc967",
          "name": "copysnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CopySnapshot?Description=Description&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33a1e36c-d1f5-41b1-9886-3ccb68ae19e6"
            }
          ]
        },
        {
          "id": "5541a26c-b16b-4bf2-acbf-8271ede3a172",
          "name": "describesnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&Owner.N=Owner.N&RestorableBy.N=RestorableBy.N&SnapshotId.N=SnapshotId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a32d2968-96b5-4988-8e49-9fd2ef5d6601"
            }
          ]
        },
        {
          "id": "4f486dea-f1e8-42b7-9f5d-da760470d073",
          "name": "describesnapshots",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshots?Attribute=Attribute&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the EBS snapshots available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06237905-523b-439c-8971-fc5f84b30842"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "173f34f7-159f-4597-85a7-73e68f9a579d",
          "name": "createsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Encrypted=Encrypted&Iops=Iops&KmsKeyId=KmsKeyId&Size=Size&SnapshotId=SnapshotId&VolumeType=VolumeType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "240a382f-9bfc-4bee-b80a-1145ee978a18"
            }
          ]
        },
        {
          "id": "ea98cbdc-764c-4703-825e-9b0d099a4338",
          "name": "deletesnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshot?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a150609-1107-4961-a11a-e9c892980afc"
            }
          ]
        },
        {
          "id": "28c58e8f-2385-45cd-928a-ff9f7886d784",
          "name": "modifysnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifySnapshotAttribute?AutoEnableIO=AutoEnableIO&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or removes permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd6aaef7-6f45-410c-a105-9a495ac05b0c"
            }
          ]
        },
        {
          "id": "c0b3f545-ac9e-45bf-aa33-144dadde191d",
          "name": "resetsnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetSnapshotAttribute?Domain=Domain&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c234896a-2f41-4cd1-85f3-96de67666794"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "347a7fcc-1e99-4ff5-ac5d-49a80e4188c3",
          "name": "createvolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateVolume?DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an EBS volume that can be attached to an instance in the same Availability Zone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d069dbd-39d4-47f1-a6de-031d7302c562"
            }
          ]
        },
        {
          "id": "0aa5892b-bb83-411e-933e-cee06dcca0c4",
          "name": "deletevolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5621eb74-63c3-4f24-8323-34a244d6056f"
            }
          ]
        },
        {
          "id": "b61aea44-626c-4892-b297-88310534284c",
          "name": "detachvolume",
          "request": {
            "url": "http://example.com/api/?Action=DetachVolume?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an EBS volume from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5e5cc82-24fe-4783-b29d-9a67b7d12a00"
            }
          ]
        },
        {
          "id": "380f987c-2caa-4615-829e-d6ac0c836ad7",
          "name": "modifyvolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVolumeAttribute?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies a volume attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79d5c601-08ac-43c2-9e88-47732844e2b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "489d70eb-1353-4258-8cdd-7e7ee1d8f08c",
          "name": "describevolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a0a1dc1-d6ab-439a-a68b-f6d324a9e499"
            }
          ]
        },
        {
          "id": "e62d85c6-ca0b-4c1d-bbc4-8760e16aca73",
          "name": "describevolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumes?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified EBS volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fcc8ca3-e3b8-4725-bea3-a7215c771848"
            }
          ]
        },
        {
          "id": "8458f3eb-9fb3-4be9-be88-ebf86d38fe12",
          "name": "enablevolumeio",
          "request": {
            "url": "http://example.com/api/?Action=EnableVolumeIO?Attribute=Attribute&CreateVolumePermission=CreateVolumePermission&DryRun=DryRun&OperationType=OperationType&SnapshotId=SnapshotId&UserGroup.N=UserGroup.N&UserId.N=UserId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables I/O operations for a volume that had I/O operations disabled because the data on the\n      volume was potentially inconsistent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c696a488-db55-490f-829f-79edec45ebf2"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "b59439de-4b2c-4186-89fc-b33cb10aad5b",
          "name": "describevolumestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeStatus?Device=Device&DryRun=DryRun&Force=Force&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of the specified volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6a30921-5f00-4039-a68f-912b226a5280"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "2a27871b-51f9-445b-a5a6-787efb187faa",
          "name": "allocateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AllocateAddress?AllocationId=AllocationId&AllowReassociation=AllowReassociation&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress=PrivateIpAddress&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Acquires an Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a1edce1-59c2-4c24-a3a7-3ff1cb7f955a"
            }
          ]
        },
        {
          "id": "c8179647-850c-4b9c-8fb6-626ab1b3aebf",
          "name": "associateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AssociateAddress?AllocationId.N=AllocationId.N&DryRun=DryRun&Filter.N=Filter.N&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates an Elastic IP address with an instance or a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54c3b9e2-0805-435b-94e3-4ae9e058e2c9"
            }
          ]
        },
        {
          "id": "0e8a86f9-ffff-4f31-83e8-3ea37e3d9136",
          "name": "describemovingaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMovingAddresses?AssociationId=AssociationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Elastic IP addresses that are being moved to the EC2-VPC platform, or that are being restored to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9da99213-e149-4eb2-9395-166f3ebf4b51"
            }
          ]
        },
        {
          "id": "6ad6eee6-d8e9-4cdd-95a3-df17c0c46fa6",
          "name": "moveaddresstovpc",
          "request": {
            "url": "http://example.com/api/?Action=MoveAddressToVpc?AllocationId=AllocationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ba8c7b9-eae8-453b-987b-0d75dba3e0f7"
            }
          ]
        },
        {
          "id": "aa7a895f-251a-435d-93a6-55ab592ba6f5",
          "name": "releaseaddress",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Releases the specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ac20ab6-6fc8-45f3-b4c4-cb7ecb31d612"
            }
          ]
        },
        {
          "id": "47cd5088-52b9-4d79-b187-e904de0dcc53",
          "name": "assignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignIpv6Addresses?AllowReassignment=AllowReassignment&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more IPv6 addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "788c7b1c-131f-42d8-9442-67db18603a97"
            }
          ]
        },
        {
          "id": "9d703d4b-5d27-46a6-a73f-2c10ec2b7ad9",
          "name": "assignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignPrivateIpAddresses?DeviceIndex=DeviceIndex&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more secondary private IP addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b26cbedb-cc14-4371-8e08-5f13a081951e"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "7b0cf0b1-2828-45ca-961a-e0efc39993c7",
          "name": "describeaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAddresses?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Elastic IP addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25674ef0-de03-436d-946e-3d4a1cdf71e3"
            }
          ]
        },
        {
          "id": "b1df6608-928e-4d5d-952f-1df7b6357ccb",
          "name": "restoreaddresstoclassic",
          "request": {
            "url": "http://example.com/api/?Action=RestoreAddressToClassic?Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Restores an Elastic IP address that was previously moved to the EC2-VPC platform back to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8af9ce6d-f128-4155-8d4d-7c0a50f622f5"
            }
          ]
        },
        {
          "id": "e6ab9c4d-b1a6-441f-bcb3-ec314d00a091",
          "name": "unassignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignPrivateIpAddresses?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more secondary private IP addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9f8f351-5414-4a76-8b7c-28fde570bdde"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "93965305-2bc4-4e14-926e-f3fd2ee8c3e3",
          "name": "disassociateaddress",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates an Elastic IP address from the instance or network interface it's associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ac1afdf-29d3-4008-adb5-48f018bca7e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "426cf6da-4f6d-4cbb-bb90-17f69291303e",
          "name": "attachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=AttachNetworkInterface?Description=Description&DryRun=DryRun&Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&PrivateIpAddress=PrivateIpAddress&PrivateIpAddresses.N=PrivateIpAddresses.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a network interface to an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a692b95c-82f7-4161-b400-aa70a91caf63"
            }
          ]
        },
        {
          "id": "b0ff3c3c-2fcd-43f6-a5bc-29368a212bef",
          "name": "createnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkInterface?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network interface in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb000c1c-4a35-4011-a4d8-636b840c7695"
            }
          ]
        },
        {
          "id": "51fdf3ab-bf6a-43ff-aa42-6799909406af",
          "name": "deletenetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkInterface?Attribute=Attribute&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dcf880ad-b5e0-426f-88a6-50c79e7a5205"
            }
          ]
        },
        {
          "id": "b44801a2-e745-4a4e-bd5b-cb4b94c35933",
          "name": "describenetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaceAttribute?DryRun=DryRun&Filter.N=Filter.N&NetworkInterfaceId.N=NetworkInterfaceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43deb7b3-e6b3-40c5-858b-348e13ddc001"
            }
          ]
        },
        {
          "id": "80cbd849-849c-4618-8b14-198e8669cce1",
          "name": "describenetworkinterfaces",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaces?AttachmentId=AttachmentId&DryRun=DryRun&Force=Force",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network interfaces."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3440aa35-f20c-48a7-84b9-bf726ab32ed7"
            }
          ]
        },
        {
          "id": "9c8969c6-4dd5-4f0a-afc0-3aac30979437",
          "name": "detachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DetachNetworkInterface?Attachment=Attachment&Description=Description&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SecurityGroupId.N=SecurityGroupId.N&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a network interface from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "186b900e-31d3-476a-aba2-5b6130ba8f27"
            }
          ]
        },
        {
          "id": "d5f2d8b6-b38e-464a-a329-257c933cfd0b",
          "name": "modifynetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyNetworkInterfaceAttribute?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2309eb6a-d878-4608-b340-3080d90ff93a"
            }
          ]
        },
        {
          "id": "1392f48c-75bf-400b-83e6-2ecfc8327c9f",
          "name": "resetnetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetNetworkInterfaceAttribute?Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5323fc09-6eb1-4281-ba97-0d54bacfb7be"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "f48d4cd7-9533-4bd3-a5fd-24343c3a2204",
          "name": "unassignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignIpv6Addresses?NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more IPv6 addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f06a2fba-79d4-4593-8469-6d76755dd655"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "590460ea-3f3c-435e-aa21-33338034f01a",
          "name": "describeinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceStatus?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a995009-6405-4ad0-ab68-a60d9c711d95"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "af48ab3f-af31-4da0-bd2b-bec2b08b00af",
          "name": "getconsoleoutput",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleOutput?DryRun=DryRun&InstanceId=InstanceId&WakeUp=WakeUp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the console output for the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04dddefc-f957-4e18-8fe9-805121ebf6d4"
            }
          ]
        }
      ]
    }
  ]
}