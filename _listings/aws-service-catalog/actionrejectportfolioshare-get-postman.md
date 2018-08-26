{
  "info": {
    "name": "AWS Service Catalog API Reject Portfolio Share",
    "_postman_id": "0670810f-38ed-437f-afdc-49fb5be6f7db",
    "description": "Rejects an offer to share a portfolio.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "08ca589e-3de5-4e1b-a1fe-cc4c3bfa6764",
          "name": "acceptPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=AcceptPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c8460bf-dc94-4477-bf25-2974ca5ba3d6"
            }
          ]
        },
        {
          "id": "a15dfcef-aad5-499d-a0e6-7c381964c2e5",
          "name": "associatePrincipalWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociatePrincipalWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN&PrincipalType=PrincipalType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates the specified principal ARN with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44aa0b98-9eae-4578-95ca-aaa82aafa65a"
            }
          ]
        },
        {
          "id": "9dc98eb9-ec5e-4e99-9e08-3a4d0cfa1c4b",
          "name": "associateProductWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociateProductWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId&SourcePortfolioId=SourcePortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a product with a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1b60079-12db-40b1-8f3d-9f4e4aa4079f"
            }
          ]
        },
        {
          "id": "8ff13e27-b0de-43c5-88f9-b95fba651536",
          "name": "createPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolio?AcceptLanguage=AcceptLanguage&Description=Description&DisplayName=DisplayName&IdempotencyToken=IdempotencyToken&ProviderName=ProviderName&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "559b75e9-7f7e-480d-b659-1c1428078eef"
            }
          ]
        },
        {
          "id": "ba7f7bfa-d6a4-4899-a68d-6ddd95527317",
          "name": "createPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d959a22-3bd8-43ad-8563-010834cfc379"
            }
          ]
        },
        {
          "id": "86b2f479-f3e4-4b2d-ab6f-9d636c6fbd59",
          "name": "deletePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68c71ed0-653c-4096-a4dc-8a1dd8ad5647"
            }
          ]
        },
        {
          "id": "3b9d595b-2c2a-4e84-af37-6cc91e6e3cc8",
          "name": "deletePortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4645ec8-f067-4703-ad40-b6d1fe393d13"
            }
          ]
        },
        {
          "id": "205fa447-3a71-4b51-a706-58b70c810461",
          "name": "describePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DescribePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information and any tags associated with the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a90bf881-fe3d-4be1-adcc-9b886ded162b"
            }
          ]
        },
        {
          "id": "19944b9a-ba3f-4c0c-881d-1bfa0245dd51",
          "name": "disassociatePrincipalFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociatePrincipalFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a previously associated principal ARN from a specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3b9c197-b7c1-43ca-b06e-043fc519bc5f"
            }
          ]
        },
        {
          "id": "45ffec39-a082-46d4-b9e4-9c3d1d3e639d",
          "name": "disassociateProductFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateProductFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates the specified product from the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74ee2b52-7308-4665-867e-35d27595fe3e"
            }
          ]
        },
        {
          "id": "8885f891-693b-4166-b1e2-c712352c68bb",
          "name": "listAcceptedPortfolioShares",
          "request": {
            "url": "http://example.com/api/?Action=ListAcceptedPortfolioShares?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists details of all portfolios for which sharing was accepted by this\n         account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fa45967-270d-40ea-8f8a-e3db810d074b"
            }
          ]
        },
        {
          "id": "1f37cbc5-ebc4-4916-9b8b-aaee83891d14",
          "name": "listConstraintsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListConstraintsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed constraint information for the specified portfolio and\n         product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae78496c-0215-4a5a-8667-6452b3e0066f"
            }
          ]
        },
        {
          "id": "8639a4a9-1835-4106-a36c-b8856bc69dd3",
          "name": "listPortfolioAccess",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolioAccess?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account IDs that have been authorized sharing of the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efe0ae70-f350-441c-a328-27dac25347b6"
            }
          ]
        },
        {
          "id": "3254c748-fe3c-4517-8b10-e11771b4f69f",
          "name": "listPortfolios",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolios?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios in the catalog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d64a58d6-b63f-4d3b-b506-cffaaf4fce70"
            }
          ]
        },
        {
          "id": "928d0999-67f2-4996-a43d-487739ae30b4",
          "name": "listPortfoliosForProduct",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfoliosForProduct?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios that the specified product is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d729021-8c19-4f82-bc0d-3b05be4dec44"
            }
          ]
        },
        {
          "id": "ffd63e80-bc17-470f-9f5d-6feae3659aeb",
          "name": "listPrincipalsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListPrincipalsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all principal ARNs associated with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9c59256-aa1f-4707-b6d2-b502b34aa402"
            }
          ]
        },
        {
          "id": "db140f5a-015f-46af-9973-b3a6ef59d08e",
          "name": "rejectPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=RejectPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Rejects an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7efd44e1-34d2-4932-b558-6e3ae0f0b8d8"
            }
          ]
        }
      ]
    },
    {
      "name": "Constraints",
      "item": [
        {
          "id": "bbc65681-f60f-44eb-b280-537347222263",
          "name": "createConstraint",
          "request": {
            "url": "http://example.com/api/?Action=CreateConstraint?AcceptLanguage=AcceptLanguage&Description=Description&IdempotencyToken=IdempotencyToken&Parameters=Parameters&PortfolioId=PortfolioId&ProductId=ProductId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e35b6b5c-9a1b-4e6f-8a6b-a3a51ceffa93"
            }
          ]
        },
        {
          "id": "6f1f5224-d043-494a-9a93-bcf5291dea6a",
          "name": "deleteConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acf670e4-f816-4e2a-938a-cbb6895d8711"
            }
          ]
        },
        {
          "id": "ec3d6eb0-23cc-40e1-8154-10c15eeb6af6",
          "name": "describeConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information for a specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dd8d3d8-fd35-4cb5-bbf6-2951f316dfb7"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "099465a7-20dd-42b4-89e9-8a3e2b74326a",
          "name": "createProduct",
          "request": {
            "url": "http://example.com/api/?Action=CreateProduct?AcceptLanguage=AcceptLanguage&Description=Description&Distributor=Distributor&IdempotencyToken=IdempotencyToken&Name=Name&Owner=Owner&ProductType=ProductType&ProvisioningArtifactParameters=ProvisioningArtifactParameters&SupportDescription=SupportDescription&SupportEmail=SupportEmail&SupportUrl=SupportUrl&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef2fd08d-bc75-46a7-a7e5-4156025e2863"
            }
          ]
        },
        {
          "id": "b4a650c0-1810-4404-a6ff-81ea405ebb9f",
          "name": "deleteProduct",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4b7213e-99c8-46c1-bb6f-eb2209883315"
            }
          ]
        },
        {
          "id": "e7c4c564-ca11-47ad-b95f-34530c7af104",
          "name": "describeProduct",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aec9cf1b-ee31-435d-b2e9-e1e8d73d257f"
            }
          ]
        },
        {
          "id": "dcc589f5-a18f-4684-951a-11791d82ebad",
          "name": "describeProductAsAdmin",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductAsAdmin?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product, run with administrator\n         access."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3727c452-2b1e-49aa-b6b0-baa26a7b7ed4"
            }
          ]
        },
        {
          "id": "9d86f175-6ac8-4e25-a5a1-7d0edc1aa39c",
          "name": "describeProductView",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductView?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11f53c5c-dcbc-4bff-9222-467e73019ad4"
            }
          ]
        },
        {
          "id": "2c67b13b-378a-4be7-bc4a-b68e73634517",
          "name": "provisionProduct",
          "request": {
            "url": "http://example.com/api/?Action=ProvisionProduct?AcceptLanguage=AcceptLanguage&NotificationArns=NotificationArns&PathId=PathId&ProductId=ProductId&ProvisionedProductName=ProvisionedProductName&ProvisioningArtifactId=ProvisioningArtifactId&ProvisioningParameters=ProvisioningParameters&ProvisionToken=ProvisionToken&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a Provision of a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "769142d2-51b4-426c-b088-45050906039e"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Artifacts",
      "item": [
        {
          "id": "fee08fc5-0b69-42de-a709-bf46ab5ab54a",
          "name": "createProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=CreateProvisioningArtifact?AcceptLanguage=AcceptLanguage&IdempotencyToken=IdempotencyToken&Parameters=Parameters&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new provisioning artifact for the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33a76a5c-2414-4392-a142-50176eaa1252"
            }
          ]
        },
        {
          "id": "ef4f4e91-4f20-4ac2-89df-c736d2a621ff",
          "name": "deleteProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "289bd648-4cb0-493f-a392-0538573e243a"
            }
          ]
        },
        {
          "id": "51b8698b-c897-46a2-adf7-a8c689ad1723",
          "name": "describeProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information about the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0e88187-3260-4519-b24d-064db2975c6f"
            }
          ]
        },
        {
          "id": "c6dcfdc4-611f-420e-ab2d-58bb518f2802",
          "name": "listProvisioningArtifacts",
          "request": {
            "url": "http://example.com/api/?Action=ListProvisioningArtifacts?AcceptLanguage=AcceptLanguage&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all provisioning artifacts associated with the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7009159b-aff7-47f5-95c0-5d0ef21ec19a"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Parameters",
      "item": [
        {
          "id": "8176a712-558b-4f14-9d71-a6eff598b5b8",
          "name": "describeProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningParameters?AcceptLanguage=AcceptLanguage&PathId=PathId&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about parameters required to provision a specified product in a\n         specified manner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fbf252b-6133-4f20-9312-02dc782006c5"
            }
          ]
        }
      ]
    },
    {
      "name": "Records",
      "item": [
        {
          "id": "6d933818-59e3-4ea1-bd52-3fd17b8a21a0",
          "name": "describeRecord",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRecord?AcceptLanguage=AcceptLanguage&Id=Id&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a paginated list of the full details of a specific request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac96ce6e-f9aa-4954-b6f7-d8a702fe006d"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch Paths",
      "item": [
        {
          "id": "db3f0446-9806-4323-bbe4-f2daed1a8a8a",
          "name": "listLaunchPaths",
          "request": {
            "url": "http://example.com/api/?Action=ListLaunchPaths?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all paths to a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8917c03d-2d65-40e2-aa3b-3b424c86043f"
            }
          ]
        }
      ]
    },
    {
      "name": "Record History",
      "item": [
        {
          "id": "53a059e5-0604-4c29-95a9-ee5b2670b699",
          "name": "listRecordHistory",
          "request": {
            "url": "http://example.com/api/?Action=ListRecordHistory?AcceptLanguage=AcceptLanguage&AccessLevelFilter=AccessLevelFilter&PageSize=PageSize&PageToken=PageToken&SearchFilter=SearchFilter",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all performed requests, in the form of RecordDetails\n         objects that are filtered as specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d398079-bf06-4c7b-9118-4eef2c5b015f"
            }
          ]
        }
      ]
    }
  ]
}